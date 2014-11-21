FaceModel.CalculateVerticesForAlignment Method  
==============================================  

Calculates vertices for alignment. <span id="syntaxSection"></span>

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
IVectorView&lt;<a href="../../../Kinect/CameraSpacePoint_Structure.md">CameraSpacePoint</a>, &gt;^ CalculateVerticesForAlignment(  
         <a href="../../FaceAlignment_Class.md">FaceAlignment</a>^ faceAlignment  
)</code></pre></td>
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
<td align="left"><pre><code>public IReadOnlyList&lt;<a href="../../../Kinect/CameraSpacePoint_Structure.md">CameraSpacePoint</a>, &gt;CalculateVerticesForAlignment (  
         <a href="../../FaceAlignment_Class.md">FaceAlignment</a>faceAlignment  
)</code></pre></td>
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
<td align="left"><pre><code>var iVectorView = faceModel.calculateVerticesForAlignment(faceAlignment);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceAlignment*    
Type: [FaceAlignment](../../FaceAlignment_Class.md)  
The face alignment.  

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[CameraSpacePoint](../../../Kinect/CameraSpacePoint_Structure.md), \>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[CameraSpacePoint](../../../Kinect/CameraSpacePoint_Structure.md), \>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[CameraSpacePoint](../../../Kinect/CameraSpacePoint_Structure.md), \>

The calculated vertices.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4ELB"></span>

See also  
========  

<span id="ID4ENB"></span>
#### Reference  

[FaceModel Class](../../FaceModel_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculateVerticesForAlignment Method
RLTitle : FaceModel.CalculateVerticesForAlignment Method
KeywordK : CalculateVerticesForAlignment method
KeywordK : FaceModel.CalculateVerticesForAlignment method
KeywordF : Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment
KeywordF : FaceModel.CalculateVerticesForAlignment
KeywordF : CalculateVerticesForAlignment
KeywordF : Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment(Microsoft.Kinect.Face.FaceAlignment)
KeywordA : M:Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment(Microsoft.Kinect.Face.FaceAlignment)
AssetID : M:Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment(Microsoft.Kinect.Face.FaceAlignment)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment
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
