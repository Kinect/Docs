IBodyFrameSource Interface  
==========================  

Represents an interface to a body frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyFrameSource** has the following members.  

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
<td align="left"><a href="IBodyFrameSource_Interface/Methods/get_BodyCount_Method.md">get_BodyCount</a></td>
<td align="left">Gets the body count.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets the current activity status of this source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the parent sensor.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">Retrieves the event data when a frame is captured.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the body index frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/OverrideAndReplaceHandTrac.md">OverrideAndReplaceHandTracking</a></td>
<td align="left">Override hand tracking the old tracking id and replace it with the new tracking id.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/OverrideHandTracking_Method.md">OverrideHandTracking</a></td>
<td align="left">Override hand tracking using the tracking id.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameSource_Interface/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
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
TOCTitle : IBodyFrameSource Interface
RLTitle : IBodyFrameSource Interface
KeywordK : IBodyFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyFrameSource
KeywordF : Microsoft.Kinect.kinect.IBodyFrameSource
KeywordA : T:Microsoft.Kinect.kinect.IBodyFrameSource
AssetID : T:Microsoft.Kinect.kinect.IBodyFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
