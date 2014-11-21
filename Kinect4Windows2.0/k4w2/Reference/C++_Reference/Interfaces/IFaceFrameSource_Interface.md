IFaceFrameSource Interface  
==========================  

Represents a FaceFrameSource. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IFaceFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IFaceFrameSource** has the following members.  

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
<td align="left"><a href="IFaceFrameSource_Interface/Methods/get_FaceFrameFeatures_Method.md">get_FaceFrameFeatures</a></td>
<td align="left">Gets the flags that indicate which face frame features data are present in this face frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets the current activity status of this face frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/get_IsTrackingIdValid_Method.md">get_IsTrackingIdValid</a></td>
<td align="left">Gets a value that indicates if the tracking ID of the face frame source is valid.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the Kinect sensor associated with the face frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">Gets the tracking ID for the face frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/GetTrackingIdLostEventData.md">GetTrackingIdLostEventData</a></td>
<td align="left">Gets the event data from a tracking ID lost frame event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the face frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/put_FaceFrameFeatures_Method.md">put_FaceFrameFeatures</a></td>
<td align="left">Sets the flags that indicate which face frame features data are present in this face frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/put_TrackingId_Method.md">put_TrackingId</a></td>
<td align="left">Sets the tracking ID of the face frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/SubscribeTrackingIdLost.md">SubscribeTrackingIdLost</a></td>
<td align="left">Subscribes to the specified event handler to the tracking ID lost event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameSource_Interface/Methods/UnsubscribeTrackingIdLost.md">UnsubscribeTrackingIdLost</a></td>
<td align="left">Unsubscribes the specified event handler that processes new frames.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IFaceFrameSource Interface
RLTitle : IFaceFrameSource Interface
KeywordK : IFaceFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IFaceFrameSource
KeywordF : Microsoft.Kinect.face.IFaceFrameSource
KeywordA : T:Microsoft.Kinect.face.IFaceFrameSource
AssetID : T:Microsoft.Kinect.face.IFaceFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
