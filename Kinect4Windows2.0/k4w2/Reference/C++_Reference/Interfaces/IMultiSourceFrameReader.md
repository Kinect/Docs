IMultiSourceFrameReader Interface  
=================================  

Represents a reader for multi source frames. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IMultiSourceFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IMultiSourceFrameReader** has the following members.  

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
<td align="left"><a href="IMultiSourceFrameReader/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">Gets the most recent multi source frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IMultiSourceFrameReader/Methods/get_FrameSourceTypes_Method.md">get_FrameSourceTypes</a></td>
<td align="left">Gets the types of frames being read by the multi source frame reader.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IMultiSourceFrameReader/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">Gets whether the multisource frame reader is paused.</td>
</tr>
<tr class="even">
<td align="left"><a href="IMultiSourceFrameReader/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the KinectSensor of the multi source frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IMultiSourceFrameReader/Methods/GetMultiSourceFrameArrived.md">GetMultiSourceFrameArrivedEventData</a></td>
<td align="left">Gets the event data when an new multisource frame arrives.</td>
</tr>
<tr class="even">
<td align="left"><a href="IMultiSourceFrameReader/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">Sets a boolean that pauses or resumes the infrared frame reader.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IMultiSourceFrameReader/Methods/SubscribeMultiSourceFrameA.md">SubscribeMultiSourceFrameArrived</a></td>
<td align="left">Subscribes to the specified event handler to process new infrared frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="IMultiSourceFrameReader/Methods/UnsubscribeMultiSourceFram.md">UnsubscribeMultiSourceFrameArrived</a></td>
<td align="left">Unsubscribes the specified event handler that processes new multisource frames.</td>
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
TOCTitle : IMultiSourceFrameReader Interface
RLTitle : IMultiSourceFrameReader Interface
KeywordK : IMultiSourceFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IMultiSourceFrameReader
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrameReader
KeywordA : T:Microsoft.Kinect.kinect.IMultiSourceFrameReader
AssetID : T:Microsoft.Kinect.kinect.IMultiSourceFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
