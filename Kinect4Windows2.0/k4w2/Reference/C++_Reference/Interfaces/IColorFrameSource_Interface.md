IColorFrameSource Interface  
===========================  

Represents a source of color frames from a Kinect sensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IColorFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IColorFrameSource** has the following members.  

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
<td align="left"><a href="IColorFrameSource_Interface/Methods/CreateFrameDescription.md">CreateFrameDescription</a></td>
<td align="left">Creates a FrameDescription object for the ColorFrame of the requested format.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameSource_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the color frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrameSource_Interface/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets the current activity status of this color frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameSource_Interface/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the KinectSensor of the color frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrameSource_Interface/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">Gets the event data from a captured frame event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameSource_Interface/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the color frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrameSource_Interface/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameSource_Interface/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
<td align="left">Unsubscribes the specified event handler that processes new frames.</td>
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
TOCTitle : IColorFrameSource Interface
RLTitle : IColorFrameSource Interface
KeywordK : IColorFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IColorFrameSource
KeywordF : Microsoft.Kinect.kinect.IColorFrameSource
KeywordA : T:Microsoft.Kinect.kinect.IColorFrameSource
AssetID : T:Microsoft.Kinect.kinect.IColorFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
