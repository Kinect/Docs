FaceFrameReader.FrameArrived Event  
==================================  

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
event TypedEventHandler&lt;<a href="../../FaceFrameReader_Class.md">FaceFrameReader</a>, <a href="../../FaceFrameArrivedEventArgs.md">FaceFrameArrivedEventArgs</a>, &gt;^ FrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../FaceFrameReader_Class.md">FaceFrameReader</a>, <a href="../../FaceFrameArrivedEventArgs.md">FaceFrameArrivedEventArgs</a>, &gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../FaceFrameReader_Class.md">FaceFrameReader</a>, <a href="../../FaceFrameArrivedEventArgs.md">FaceFrameArrivedEventArgs</a>, &gt; FrameArrived</code></pre></td>
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
faceFrameReader.addEventListener(&quot;framearrived&quot;, onFrameArrived);  
faceFrameReader.removeEventListener(&quot;framearrived&quot;, onFrameArrived);  

- or -  

faceFrameReader.onframearrived = onFrameArrived;</code></pre></td>
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

[FaceFrameReader Class](../../FaceFrameReader_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameArrived Event
RLTitle : FaceFrameReader.FrameArrived Event
KeywordK : FrameArrived event
KeywordK : FaceFrameReader.FrameArrived event
KeywordF : Microsoft.Kinect.Face.FaceFrameReader.FrameArrived
KeywordF : FaceFrameReader.FrameArrived
KeywordF : FrameArrived
KeywordF : Microsoft.Kinect.Face.FaceFrameReader.FrameArrived
KeywordA : E:Microsoft.Kinect.Face.FaceFrameReader.FrameArrived
AssetID : E:Microsoft.Kinect.Face.FaceFrameReader.FrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameReader.FrameArrived
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
