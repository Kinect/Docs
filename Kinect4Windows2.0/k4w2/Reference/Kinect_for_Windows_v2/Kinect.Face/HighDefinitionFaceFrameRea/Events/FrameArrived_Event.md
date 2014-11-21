HighDefinitionFaceFrameReader.FrameArrived Event  
================================================  

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
event TypedEventHandler&lt;<a href="../../HighDefinitionFaceFrameRea.md">HighDefinitionFaceFrameReader</a>, <a href="../../HighDefinitionFaceFrameArr.md">HighDefinitionFaceFrameArrivedEventArgs</a>, &gt;^ FrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../HighDefinitionFaceFrameRea.md">HighDefinitionFaceFrameReader</a>, <a href="../../HighDefinitionFaceFrameArr.md">HighDefinitionFaceFrameArrivedEventArgs</a>, &gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../HighDefinitionFaceFrameRea.md">HighDefinitionFaceFrameReader</a>, <a href="../../HighDefinitionFaceFrameArr.md">HighDefinitionFaceFrameArrivedEventArgs</a>, &gt; FrameArrived</code></pre></td>
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
highDefinitionFaceFrameReader.addEventListener(&quot;framearrived&quot;, onFrameArrived);  
highDefinitionFaceFrameReader.removeEventListener(&quot;framearrived&quot;, onFrameArrived);  

- or -  

highDefinitionFaceFrameReader.onframearrived = onFrameArrived;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[HighDefinitionFaceFrameReader Class](../../HighDefinitionFaceFrameRea.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameArrived Event
RLTitle : HighDefinitionFaceFrameReader.FrameArrived Event
KeywordK : FrameArrived event
KeywordK : HighDefinitionFaceFrameReader.FrameArrived event
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.FrameArrived
KeywordF : HighDefinitionFaceFrameReader.FrameArrived
KeywordF : FrameArrived
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.FrameArrived
KeywordA : E:Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.FrameArrived
AssetID : E:Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.FrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.FrameArrived
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
