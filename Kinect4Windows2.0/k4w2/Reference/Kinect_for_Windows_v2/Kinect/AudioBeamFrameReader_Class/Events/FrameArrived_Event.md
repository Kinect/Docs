AudioBeamFrameReader.FrameArrived Event  
=======================================  

Event that fires whenever a frame is captured.<span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
event TypedEventHandler&lt;<a href="../../AudioBeamFrameReader_Class.md">AudioBeamFrameReader</a>, <a href="../../AudioBeamFrameArrivedEvent.md">AudioBeamFrameArrivedEventArgs</a>&gt;^ FrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../AudioBeamFrameReader_Class.md">AudioBeamFrameReader</a>, <a href="../../AudioBeamFrameArrivedEvent.md">AudioBeamFrameArrivedEventArgs</a>&gt;^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../AudioBeamFrameReader_Class.md">AudioBeamFrameReader</a>, <a href="../../AudioBeamFrameArrivedEvent.md">AudioBeamFrameArrivedEventArgs</a>&gt; FrameArrived</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>function onFrameArrived(eventArgs) { /* Your code */ }  

// addEventListener syntax  
audioBeamFrameReader.addEventListener(&quot;framearrived&quot;, onFrameArrived);  
audioBeamFrameReader.removeEventListener(&quot;framearrived&quot;, onFrameArrived);  

- or -  

audioBeamFrameReader.onframearrived = onFrameArrived;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[AudioBeamFrameReader Class](../../AudioBeamFrameReader_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameArrived Event
RLTitle : AudioBeamFrameReader.FrameArrived Event
KeywordK : FrameArrived event
KeywordK : AudioBeamFrameReader.FrameArrived event
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader.FrameArrived
KeywordF : AudioBeamFrameReader.FrameArrived
KeywordF : FrameArrived
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader.FrameArrived
KeywordA : E:WindowsPreview.Kinect.AudioBeamFrameReader.FrameArrived
AssetID : E:WindowsPreview.Kinect.AudioBeamFrameReader.FrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameReader.FrameArrived
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
