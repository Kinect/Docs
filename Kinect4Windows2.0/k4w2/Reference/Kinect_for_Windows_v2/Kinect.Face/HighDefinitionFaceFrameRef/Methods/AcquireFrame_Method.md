HighDefinitionFaceFrameReference.AcquireFrame Method  
====================================================  

Gets a container for one frame of high-definition face frame data. <span id="syntaxSection"></span>

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
<a href="../../HighDefinitionFaceFrame.md">HighDefinitionFaceFrame</a>^ AcquireFrame()</code></pre></td>
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
<td align="left"><pre><code>public <a href="../../HighDefinitionFaceFrame.md">HighDefinitionFaceFrame</a>AcquireFrame ()</code></pre></td>
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
<td align="left"><pre><code>var highDefinitionFaceFrame = highDefinitionFaceFrameReference.acquireFrame();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [HighDefinitionFaceFrame](../../HighDefinitionFaceFrame.md)  
Upon success, returns the frame reference corresponding to this event, which must be disposed. Can return null if the data is not available.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E1"></span>

See also  
========  

<span id="ID4E3"></span>
#### Reference  

[HighDefinitionFaceFrameReference Class](../../HighDefinitionFaceFrameRef.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AcquireFrame Method
RLTitle : HighDefinitionFaceFrameReference.AcquireFrame Method
KeywordK : AcquireFrame method
KeywordK : HighDefinitionFaceFrameReference.AcquireFrame method
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.AcquireFrame
KeywordF : HighDefinitionFaceFrameReference.AcquireFrame
KeywordF : AcquireFrame
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.AcquireFrame
KeywordA : M:Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.AcquireFrame
AssetID : M:Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.AcquireFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.AcquireFrame
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
