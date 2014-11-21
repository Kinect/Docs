Body tracking  
=============  

This topic discusses how to use the body tracking capabilities of the Kinect Sensor.  

<span id="ID4ES"></span>

BodyFrame  
=========  

The BodyFrame, accessed from the BodyFrameReader, provides access to the individual bodies through the method `GetAndRefreshBodyData`. This method takes an IVector\<Body\> and updates the Body instances with the values from the current BodyFrame. If the IVector is null, then IVector will be filled with a new Body object. The input vector must have the size `BodyFrameSource::BodyCount`.  

This pattern allows for zero-allocation retrieval of the Body object, while still allowing for future additions to the class without breaking.  

The following code example shows how to open a sensor, subscribe to the BodyFrameArrived event, and fill the bodies vector with the current body data.  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>   
void MainPage::InitKinect()  
{  
  KinectSensor^ sensor = KinectSensor::GetDefault();  
  sensor-&gt;Open();  
  bodyReader = sensor-&gt;BodyFrameSource-&gt;OpenReader();  
  bodyReader-&gt;FrameArrived +=   
   ref new TypedEventHandler&lt;typename BodyFrameArrivedEventArgs^&gt; (this,                   
                        &amp;MainPage::OnBodyFrameArrived);  
  bodies = ref new Platform::Collections::Vector&lt;Body^&gt;(6);  
}  

void MainPage::OnBodyFrameArrived(BodyFrameReader ^sender, BodyFrameArrivedEventArgs ^eventArgs){  
  BodyFrame ^frame = eventArgs-&gt;FrameReference-&gt;AcquireFrame();  
  if (frame != nullptr){  
      frame-&gt;GetAndRefreshBodyData(bodies);  
  }  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EDB"></span>

Body data  
=========  

The bodies tracked by NUI are oriented as if the player were looking into a mirror. This facilitates natural interactions with the game world. For example, to have the player touch an object on the right hand side of the screen, use the right joints:  

-   JointType::HandRight  
-   JointType::HandTipRight  
-   JointType::ThumbRight  

<span id="ID4ETB"></span>

Joint normals  
=============  

There is a normal for each body joint that describes rotation. Rotation is expressed as the vector (in world space) perpendicular to the attached bones in the joint hierarchy. For example, to determine the roll of the right elbow, the immediate parent joint in the hierarchy, the right shoulder, is used to determine the plane of the bone.  

<span id="ID4E1B"></span>

Joint hierarchy  
===============  

Joint hierarchy flows from the center of the body to the extremities, and from the top-most to the bottom-most joints. These connections are described as bones. For example, the bones of the right arm (not counting the thumb) consist of the following connections:  

-   Right hand – Right hand tip  
-   Right wrist – Right hand  
-   Right elbow – Right wrist  
-   Right shoulder – Right elbow  

By convention, bones are described as parent–child connections.  

<span id="ID4EOC"></span>

What is HandData?  
=================  

The HandLeftState and HandRightState properties provide information about the state of each of the player's hands. You can use this information to determine if a player is interacting with an object in the title's world.  

The states returned are:  

-   Open  
-   Closed  
-   Lasso  
-   NotTracked  
-   Unknown  

<span id="ID4EDD"></span>

Using the lasso hand state  
==========================  

Although it is straightforward to think of scenarios in which the open and closed hand states are useful, the lasso state is more complex. The lasso hand state is a closed hand with the middle and index fingers both up. It is like a pointer hand, but with both the index and middle finger. Like the peace sign but the two fingers are together instead of separated. If the hand is large enough and close enough, one finger will likely work as well. The second finger is required to create something large enough in depth to be recognized.  

There are no strict rules for using the lasso state. The lasso state may be evaluated in gesture mechanics such as:  

-   Selecting an area by using a circular motion  
-   Activating a region, such as a screen object  
-   Drawing on the screen  
-   Rotating a screen object (for example, rotating a player's avatar during character creation)  

There are countless uses for the lasso state. Specific uses will vary by title design and the intended player experience.  

<span id="ID4EYD"></span>

Expressions, activities, and appearance  
=======================================  

These results are not calculated for the body and exist here for compatibility reasons with Xbox One. If you would like to see expression, activity or appearance information, please see [Face tracking](Face_tracking.md) for more information.  

<span id="ID4EDE"></span>

Engagement  
==========  

In previous releases, the Body::Enaged property allowed you to determine how engaged a particular body is with the console. This property has been deprecated. Please see [Face tracking](Face_tracking.md) for how to obtain this data.  

<span id="ID4EOE"></span>

Aligning images and body  
========================  

There are times when you might want to determine the location of points from depth, color, or camera space in another space. For example, if you want to know where in a color image the player’s head is located.  

You can use the CoordinateMapper pay-to-play class, which is available from the KinectSensor instance. The following code example shows how to get the color pixel (ColorSpacePoint) represented by the body's head joint.  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>void MainPage::OnBodyFrameArrived(Platform::Object ^sender,   
                                  BodyFrameArrivedEventArgs ^eventArgs){  
{  
  BodyFrame ^frame = eventArgs-&gt;FrameReference-&gt;AcquireFrame();  
  if (frame != nullptr)  
  {  
    frame-&gt;GetAndRefreshBodyData(bodies);      

    for each (Body ^body in bodies)  
    {  
      Joint headJoint = body-&gt;Joints-&gt;Lookup(JointType::Head);  
      CameraSpacePoint headLocation = headJoint.Position;  
      TrackingState headTrackingState = headJoint.TrackingState;  
          
      CoordinateMapper ^mapper =   
        frame-&gt;BodyFrameSource-&gt;KinectSensor-&gt;CoordinateMapper;  
      ColorSpacePoint headPoint = mapper-&gt;MapCameraPointToColorSpace(headLocation);  
    }  
  }  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EZE"></span>

Using joint tracking state in filtering  
=======================================  

Joints that are inferred are more likely to have temporary spike noises because they are less accurate. Also, the random noise levels are usually higher for inferred joints. In practice, for Kinect games, developers should consider a joint’s tracking state to be valuable information about the quality of the joint data, and apply a more aggressive smoothing filter when a joint’s state is inferred. This can easily be done by checking the joint's tracking state in the filter’s implementation and adaptively updating the filter parameters based on the joint's tracking state. Also, filters that are specifically more powerful in removing spike noise should be applied when a joint's state is inferred.  

To learn more about joint filtering techniques, read the topic on Joint Filtering Best Practices.  

<span id="ID4EBF"></span>

See also  
========  

[Kinect for Windows Programming Guide](../Programming_Guide.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Body tracking
RLTitle : Body tracking
KeywordA : O:Microsoft.Kinect.bodytracking_v2
KeywordA : ef16f955-7287-c5d3-433b-bf2500f03928
KeywordK : Body tracking
KeywordK : body
AssetID : ef16f955-7287-c5d3-433b-bf2500f03928
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
