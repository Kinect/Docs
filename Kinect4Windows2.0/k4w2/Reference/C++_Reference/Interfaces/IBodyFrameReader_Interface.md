IBodyFrameReader Interface  
==========================  

Represents an interface to a body frame source reader. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyFrameReader** has the following members.  

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
<td align="left"><a href="IBodyFrameReader_Interface/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">Gets the most recent frame. It may return null if no frame is available.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/get_BodyFrameSource_Method.md">get_BodyFrameSource</a></td>
<td align="left">Gets the body frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">Gets a boolean value that indicates if this reader is paused.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">Gets the event data when a new frame arrives.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">Sets a boolean value that pauses or resumes the reader.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">Subscribes to the specified event handler to process new frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
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
TOCTitle : IBodyFrameReader Interface
RLTitle : IBodyFrameReader Interface
KeywordK : IBodyFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyFrameReader
KeywordF : Microsoft.Kinect.kinect.IBodyFrameReader
KeywordA : T:Microsoft.Kinect.kinect.IBodyFrameReader
AssetID : T:Microsoft.Kinect.kinect.IBodyFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
