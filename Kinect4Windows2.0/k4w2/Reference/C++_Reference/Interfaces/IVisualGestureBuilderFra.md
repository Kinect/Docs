IVisualGestureBuilderFrameSource Interface  
==========================================  

Represents a Visual Gesture Builder frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IVisualGestureBuilderFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IVisualGestureBuilderFrameSource** has the following members.  

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
<td align="left"><a href="IVisualGestureBuilderFra/Methods/AddGesture_Method.md">AddGesture</a></td>
<td align="left">Adds the specified gesture to the Visual Gesture Builder frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/AddGestures_Method.md">AddGestures</a></td>
<td align="left">Adds the specified list of gestures to the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_GestureCount_Method.md">get_GestureCount</a></td>
<td align="left">Gets the number of gestures associated with the Visual Gesture Builder frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_Gestures_Method.md">get_Gestures</a></td>
<td align="left">Gets a collection of gestures associated with the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_HorizontalMirror.md">get_HorizontalMirror</a></td>
<td align="left">Gets a value indicating whether horizontal mirroring should be used.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets a value indicating if the Visual Gesture Builder frame source is active.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_IsTrackingIdValid.md">get_IsTrackingIdValid</a></td>
<td align="left">Gets a value indicating if the tracking ID associated with the frame sourcec is valid.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the Kinect sensor associated with the frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">Gets the tracking ID.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/GetIsEnabled_Method.md">GetIsEnabled</a></td>
<td align="left">Gets a value indicating if the specified gesture is enabled for the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/GetTrackingIdLostEventData.md">GetTrackingIdLostEventData</a></td>
<td align="left">Gets the event data from a tracking ID lost frame event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Opens a new frame reader.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/put_HorizontalMirror.md">put_HorizontalMirror</a></td>
<td align="left">Sets a value indicating whether horizontal mirroring should be used.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/put_TrackingId_Method.md">put_TrackingId</a></td>
<td align="left">Sets the tracking ID of the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/RemoveGesture_Method.md">RemoveGesture</a></td>
<td align="left">Removes the specified gesture from the Visual Gesture Builder frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/SetIsEnabled_Method.md">SetIsEnabled</a></td>
<td align="left">Sets whether the specified gesture is enabled for the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/SubscribeTrackingIdLost.md">SubscribeTrackingIdLost</a></td>
<td align="left">Subscribes to the specified event handler to the tracking ID lost event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFra/Methods/UnsubscribeTrackingIdLost.md">UnsubscribeTrackingIdLost</a></td>
<td align="left">Unsubscribes the specified event handler that processes new frames.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IVisualGestureBuilderFrameSource Interface
RLTitle : IVisualGestureBuilderFrameSource Interface
KeywordK : IVisualGestureBuilderFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IVisualGestureBuilderFrameSource
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
KeywordA : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
AssetID : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
