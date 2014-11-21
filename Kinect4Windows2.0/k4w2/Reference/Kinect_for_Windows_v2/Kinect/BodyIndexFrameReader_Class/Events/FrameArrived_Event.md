BodyIndexFrameReader.FrameArrived Event  
=======================================  

Event that fires when a new frame is ready. <span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../BodyIndexFrameReader_Class.md">BodyIndexFrameReader</a>, <a href="../../BodyIndexFrameArrivedEvent.md">BodyIndexFrameArrivedEventArgs</a>&gt;^ FrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../BodyIndexFrameReader_Class.md">BodyIndexFrameReader</a>, <a href="../../BodyIndexFrameArrivedEvent.md">BodyIndexFrameArrivedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../BodyIndexFrameReader_Class.md">BodyIndexFrameReader</a>, <a href="../../BodyIndexFrameArrivedEvent.md">BodyIndexFrameArrivedEventArgs</a>&gt; FrameArrived</code></pre></td>
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
bodyIndexFrameReader.addEventListener(&quot;framearrived&quot;, onFrameArrived);  
bodyIndexFrameReader.removeEventListener(&quot;framearrived&quot;, onFrameArrived);  

- or -  

bodyIndexFrameReader.onframearrived = onFrameArrived;</code></pre></td>
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

[BodyIndexFrameReader Class](../../BodyIndexFrameReader_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameArrived Event
RLTitle : BodyIndexFrameReader.FrameArrived Event
KeywordK : FrameArrived event
KeywordK : BodyIndexFrameReader.FrameArrived event
KeywordF : WindowsPreview.Kinect.BodyIndexFrameReader.FrameArrived
KeywordF : BodyIndexFrameReader.FrameArrived
KeywordF : FrameArrived
KeywordF : WindowsPreview.Kinect.BodyIndexFrameReader.FrameArrived
KeywordA : E:WindowsPreview.Kinect.BodyIndexFrameReader.FrameArrived
AssetID : E:WindowsPreview.Kinect.BodyIndexFrameReader.FrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyIndexFrameReader.FrameArrived
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
