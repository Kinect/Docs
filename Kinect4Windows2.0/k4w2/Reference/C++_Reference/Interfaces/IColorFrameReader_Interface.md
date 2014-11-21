IColorFrameReader Interface  
===========================  

Represents a reader for color frames. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IColorFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IColorFrameReader** has the following members.  

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
<td align="left"><a href="IColorFrameReader_Interface/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">Gets the most recent color frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameReader_Interface/Methods/get_ColorFrameSource_Method.md">get_ColorFrameSource</a></td>
<td align="left">Gets the source of the color frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrameReader_Interface/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">Gets a boolean value that indicates if this reader is paused.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameReader_Interface/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">Gets the event data when a new frame arrives.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrameReader_Interface/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">Sets a boolean value that pauses or resumes the reader.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrameReader_Interface/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">Subscribes to the specified event handler to process new frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrameReader_Interface/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
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
TOCTitle : IColorFrameReader Interface
RLTitle : IColorFrameReader Interface
KeywordK : IColorFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IColorFrameReader
KeywordF : Microsoft.Kinect.kinect.IColorFrameReader
KeywordA : T:Microsoft.Kinect.kinect.IColorFrameReader
AssetID : T:Microsoft.Kinect.kinect.IColorFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
