VisualGestureBuilderFrameReader.FrameArrived Event  
==================================================  

Occurs when a new frame is ready.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../VisualGestureBuilderFrameR.md">VisualGestureBuilderFrameReader</a>, <a href="../../VisualGestureBuilderFrameA.md">VisualGestureBuilderFrameArrivedEventArgs</a>&gt;^ FrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../VisualGestureBuilderFrameR.md">VisualGestureBuilderFrameReader</a>, <a href="../../VisualGestureBuilderFrameA.md">VisualGestureBuilderFrameArrivedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../VisualGestureBuilderFrameR.md">VisualGestureBuilderFrameReader</a>, <a href="../../VisualGestureBuilderFrameA.md">VisualGestureBuilderFrameArrivedEventArgs</a>&gt; FrameArrived</code></pre></td>
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
visualGestureBuilderFrameReader.addEventListener(&quot;framearrived&quot;, onFrameArrived);  
visualGestureBuilderFrameReader.removeEventListener(&quot;framearrived&quot;, onFrameArrived);  

- or -  

visualGestureBuilderFrameReader.onframearrived = onFrameArrived;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[VisualGestureBuilderFrameReader Class](../../VisualGestureBuilderFrameR.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../../Kinect.VisualGestureBuilder.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameArrived Event
RLTitle : VisualGestureBuilderFrameReader.FrameArrived Event
KeywordK : FrameArrived event
KeywordK : VisualGestureBuilderFrameReader.FrameArrived event
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameReader.FrameArrived
KeywordF : VisualGestureBuilderFrameReader.FrameArrived
KeywordF : FrameArrived
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameReader.FrameArrived
KeywordA : E:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameReader.FrameArrived
AssetID : E:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameReader.FrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameReader.FrameArrived
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
