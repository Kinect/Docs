FaceFrameReference.AcquireFrame Method  
======================================  

Gets a container for one frame of face frame data. <span id="syntaxSection"></span>

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
<a href="../../FaceFrame_Class.md">FaceFrame</a>^ AcquireFrame()</code></pre></td>
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
<td align="left"><pre><code>public <a href="../../FaceFrame_Class.md">FaceFrame</a>AcquireFrame ()</code></pre></td>
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
<td align="left"><pre><code>var faceFrame = faceFrameReference.acquireFrame();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [FaceFrame](../../FaceFrame_Class.md)  
 Upon success, returns the [FaceFrameReference](../../FaceFrameReference_Class.md) corresponding to this event, which must be disposed. Can return null if the data is not available.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[FaceFrameReference Class](../../FaceFrameReference_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AcquireFrame Method
RLTitle : FaceFrameReference.AcquireFrame Method
KeywordK : AcquireFrame method
KeywordK : FaceFrameReference.AcquireFrame method
KeywordF : Microsoft.Kinect.Face.FaceFrameReference.AcquireFrame
KeywordF : FaceFrameReference.AcquireFrame
KeywordF : AcquireFrame
KeywordF : Microsoft.Kinect.Face.FaceFrameReference.AcquireFrame
KeywordA : M:Microsoft.Kinect.Face.FaceFrameReference.AcquireFrame
AssetID : M:Microsoft.Kinect.Face.FaceFrameReference.AcquireFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameReference.AcquireFrame
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
