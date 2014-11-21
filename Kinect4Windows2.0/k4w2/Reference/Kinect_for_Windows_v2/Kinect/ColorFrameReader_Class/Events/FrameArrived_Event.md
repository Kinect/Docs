ColorFrameReader.FrameArrived Event  
===================================  

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
event TypedEventHandler&lt;<a href="../../ColorFrameReader_Class.md">ColorFrameReader</a>, <a href="../../ColorFrameArrivedEventArgs.md">ColorFrameArrivedEventArgs</a>&gt;^ FrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../ColorFrameReader_Class.md">ColorFrameReader</a>, <a href="../../ColorFrameArrivedEventArgs.md">ColorFrameArrivedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../ColorFrameReader_Class.md">ColorFrameReader</a>, <a href="../../ColorFrameArrivedEventArgs.md">ColorFrameArrivedEventArgs</a>&gt; FrameArrived</code></pre></td>
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
colorFrameReader.addEventListener(&quot;framearrived&quot;, onFrameArrived);  
colorFrameReader.removeEventListener(&quot;framearrived&quot;, onFrameArrived);  

- or -  

colorFrameReader.onframearrived = onFrameArrived;</code></pre></td>
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

[ColorFrameReader Class](../../ColorFrameReader_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameArrived Event
RLTitle : ColorFrameReader.FrameArrived Event
KeywordK : FrameArrived event
KeywordK : ColorFrameReader.FrameArrived event
KeywordF : WindowsPreview.Kinect.ColorFrameReader.FrameArrived
KeywordF : ColorFrameReader.FrameArrived
KeywordF : FrameArrived
KeywordF : WindowsPreview.Kinect.ColorFrameReader.FrameArrived
KeywordA : E:WindowsPreview.Kinect.ColorFrameReader.FrameArrived
AssetID : E:WindowsPreview.Kinect.ColorFrameReader.FrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrameReader.FrameArrived
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
