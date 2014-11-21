IDepthFrameSource Interface  
===========================  

Represents a source of depth frames from a KinectSensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IDepthFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IDepthFrameSource** has the following members.  

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
<td align="left"><a href="IDepthFrameSource/Methods/get.md">get_DepthMaxReliableDistance</a></td>
<td align="left">Gets the maximum reliable depth of the depth frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource/Methods/get.md">get_DepthMinReliableDistance</a></td>
<td align="left">Gets the minimum reliable depth of the depth frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource/Methods/get_FrameDescription.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the depth frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets the current activity status of this depth frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the Kinect sensor object of the depth frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">Gets the event data from a captured frame event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the depth frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
<td align="left">Unsubscribes the specified event handler that processes new depth frames.</td>
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
TOCTitle : IDepthFrameSource Interface
RLTitle : IDepthFrameSource Interface
KeywordK : IDepthFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IDepthFrameSource
KeywordF : Microsoft.Kinect.kinect.IDepthFrameSource
KeywordA : T:Microsoft.Kinect.kinect.IDepthFrameSource
AssetID : T:Microsoft.Kinect.kinect.IDepthFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
