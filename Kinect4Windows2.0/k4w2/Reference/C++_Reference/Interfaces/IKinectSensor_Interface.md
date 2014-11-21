IKinectSensor Interface  
=======================  

Represents a Kinect sensor device. <span id="syntaxSection"></span>

Syntax  
======  

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
<td align="left"><pre><code>interface IKinectSensor : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectSensor** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/Close_Method.md">Close</a></td>
<td align="left">Gracefully cleans up running streams.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_AudioSource_Method.md">get_AudioSource</a></td>
<td align="left">Gets the audio source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_BodyFrameSource_Method.md">get_BodyFrameSource</a></td>
<td align="left">Gets the body source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_BodyIndexFrameSource.md">get_BodyIndexFrameSource</a></td>
<td align="left">Gets the body index source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_ColorFrameSource_Method.md">get_ColorFrameSource</a></td>
<td align="left">Gets the color source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_CoordinateMapper_Method.md">get_CoordinateMapper</a></td>
<td align="left">Gets the coordinate mapper.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_DepthFrameSource_Method.md">get_DepthFrameSource</a></td>
<td align="left">Gets the depth source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_InfraredFrameSource.md">get_InfraredFrameSource</a></td>
<td align="left">Gets the infrared source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_IsAvailable_Method.md">get_IsAvailable</a></td>
<td align="left">Gets a boolean value that indicates whether the Kinect sensor is available.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_IsOpen_Method.md">get_IsOpen</a></td>
<td align="left">Gets a boolean value that indicates whether the Kinect sensor has any open streams.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_KinectCapabilities.md">get_KinectCapabilities</a></td>
<td align="left">Gets the capabilities of the Kinect sensor.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get.md">get_LongExposureInfraredFrameSource</a></td>
<td align="left">Gets the long exposure infrared frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_UniqueKinectId_Method.md">get_UniqueKinectId</a></td>
<td align="left">Gets the unique ID of the Kinect sensor.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/GetIsAvailableChangedEvent.md">GetIsAvailableChangedEventData</a></td>
<td align="left">Gets the event data when when the availability of the Kinect sensor changes.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/Open_Method.md">Open</a></td>
<td align="left">Starts streaming data from the Kinect using a specified access mode.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/OpenMultiSourceFrameReader.md">OpenMultiSourceFrameReader</a></td>
<td align="left">Opens a new stream reader.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/SubscribeIsAvailableChanged.md">SubscribeIsAvailableChanged</a></td>
<td align="left">Subscribes an event handler that is raised when the availability of the Kinect Sensor changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/UnsubscribeIsAvailableChan.md">UnsubscribeIsAvailableChanged</a></td>
<td align="left">Unsubscribes an event handler that is raised when the availability of the Kinect Sensor changes.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IKinectSensor Interface
RLTitle : IKinectSensor Interface
KeywordK : IKinectSensor interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectSensor
KeywordF : Microsoft.Kinect.kinect.IKinectSensor
KeywordA : T:Microsoft.Kinect.kinect.IKinectSensor
AssetID : T:Microsoft.Kinect.kinect.IKinectSensor
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
