IBodyIndexFrameSource Interface  
===============================  

Represents a source of body index frames from a KinectSensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyIndexFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyIndexFrameSource** has the following members.  

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
<td align="left"><a href="IBodyIndexFrameSource/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the body index frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrameSource/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets whether the body index frame source is active.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrameSource/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the KinectSensor of the body index frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrameSource/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">Retrieves the body index frame source event data when a frame is captured.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrameSource/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the body index frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrameSource/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrameSource/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
<td align="left">Unsubscribes a subscribed event handler when a frame has been captured.</td>
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
TOCTitle : IBodyIndexFrameSource Interface
RLTitle : IBodyIndexFrameSource Interface
KeywordK : IBodyIndexFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyIndexFrameSource
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameSource
KeywordA : T:Microsoft.Kinect.kinect.IBodyIndexFrameSource
AssetID : T:Microsoft.Kinect.kinect.IBodyIndexFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
