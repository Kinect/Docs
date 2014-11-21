FaceModelBuilder.CaptureStatusChanged Event  
===========================================  

Occurs when the capture status changes.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../FaceModelBuilder_Class.md">FaceModelBuilder</a>, <a href="../../CaptureStatusChangedEventA.md">CaptureStatusChangedEventArgs</a>&gt;^ CaptureStatusChanged {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../FaceModelBuilder_Class.md">FaceModelBuilder</a>, <a href="../../CaptureStatusChangedEventA.md">CaptureStatusChangedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../FaceModelBuilder_Class.md">FaceModelBuilder</a>, <a href="../../CaptureStatusChangedEventA.md">CaptureStatusChangedEventArgs</a>&gt; CaptureStatusChanged</code></pre></td>
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
<td align="left"><pre><code>function onCaptureStatusChanged(eventArgs) { /* Your code */ }  

// addEventListener syntax  
faceModelBuilder.addEventListener(&quot;capturestatuschanged&quot;, onCaptureStatusChanged);  
faceModelBuilder.removeEventListener(&quot;capturestatuschanged&quot;, onCaptureStatusChanged);  

- or -  

faceModelBuilder.oncapturestatuschanged = onCaptureStatusChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[FaceModelBuilder Class](../../FaceModelBuilder_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CaptureStatusChanged Event
RLTitle : FaceModelBuilder.CaptureStatusChanged Event
KeywordK : CaptureStatusChanged event
KeywordK : FaceModelBuilder.CaptureStatusChanged event
KeywordF : Microsoft.Kinect.Face.FaceModelBuilder.CaptureStatusChanged
KeywordF : FaceModelBuilder.CaptureStatusChanged
KeywordF : CaptureStatusChanged
KeywordF : Microsoft.Kinect.Face.FaceModelBuilder.CaptureStatusChanged
KeywordA : E:Microsoft.Kinect.Face.FaceModelBuilder.CaptureStatusChanged
AssetID : E:Microsoft.Kinect.Face.FaceModelBuilder.CaptureStatusChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModelBuilder.CaptureStatusChanged
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
