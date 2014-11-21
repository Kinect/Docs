FaceModelData.ProduceFaceModel Method  
=====================================  

Produces a face model. <span id="syntaxSection"></span>

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
<a href="../../FaceModel_Class.md">FaceModel</a>^ ProduceFaceModel()</code></pre></td>
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
<td align="left"><pre><code>public <a href="../../FaceModel_Class.md">FaceModel</a>ProduceFaceModel ()</code></pre></td>
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
<td align="left"><pre><code>var faceModel = faceModelData.produceFaceModel();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [FaceModel](../../FaceModel_Class.md)  
A face model.  

<span id="remarks"></span>

Remarks  
=======  

Use this method, instead of [ProduceFaceModelAsync](ProduceFaceModelAsync_Method.md), to control the priority and resource use of the face model calculations by wrapping this method in its own thread.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[FaceModelData Class](../../FaceModelData_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProduceFaceModel Method
RLTitle : FaceModelData.ProduceFaceModel Method
KeywordK : ProduceFaceModel method
KeywordK : FaceModelData.ProduceFaceModel method
KeywordF : Microsoft.Kinect.Face.FaceModelData.ProduceFaceModel
KeywordF : FaceModelData.ProduceFaceModel
KeywordF : ProduceFaceModel
KeywordF : Microsoft.Kinect.Face.FaceModelData.ProduceFaceModel
KeywordA : M:Microsoft.Kinect.Face.FaceModelData.ProduceFaceModel
AssetID : M:Microsoft.Kinect.Face.FaceModelData.ProduceFaceModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModelData.ProduceFaceModel
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
