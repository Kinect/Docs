FaceModel Constructor (Single, Generic IMapView)  
================================================  

Initializes a new instance of the face model. <span id="syntaxSection"></span>

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
FaceModel(  
         float32 scale,  
         IMapView&lt;<a href="../../FaceShapeDeformations.md">FaceShapeDeformations</a>, float32, &gt;^ faceShapeDeformations  
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
<td align="left"><pre><code>public FaceModel (  
         float scale,  
         IReadOnlyDictionary&lt;<a href="../../FaceShapeDeformations.md">FaceShapeDeformations</a>, float, &gt;faceShapeDeformations  
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
<td align="left"><pre><code>var faceModel = new Microsoft.Kinect.Face.FaceModel(scale, faceShapeDeformations);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*scale*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

The scale of the model.  

*faceShapeDeformations*    
[C++] Type: [IMapView](http://msdn.microsoft.com/en-us/library/br226037.aspx)\<[FaceShapeDeformations](../../FaceShapeDeformations.md), float32, \>
  [C\#] Type: [IReadOnlyDictionary](http://msdn.microsoft.com/en-us/library/hh136548.aspx)\<[FaceShapeDeformations](../../FaceShapeDeformations.md), [float](http://msdn.microsoft.com/en-us/library/system.single.aspx), \>
  [JavaScript] Type: [IMapView](http://msdn.microsoft.com/en-us/library/br226037.aspx)\<[FaceShapeDeformations](../../FaceShapeDeformations.md), Number, \>
   

The face shape deformations of the model.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EWB"></span>

See also  
========  

<span id="ID4EYB"></span>
#### Reference  

[FaceModel Class](../../FaceModel_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceModel Constructor (Single, Generic IMapView)
RLTitle : FaceModel Constructor (Single, Generic IMapView)
KeywordA : M:Microsoft.Kinect.Face.FaceModel.#ctor(System.Single,Windows.Foundation.Collections.IMapView{Microsoft.Kinect.Face.FaceShapeDeformations,System.Single,Microsoft.Kinect.Face.FaceShapeDeformations,System.Single})
AssetID : M:Microsoft.Kinect.Face.FaceModel.#ctor(System.Single,Windows.Foundation.Collections.IMapView{Microsoft.Kinect.Face.FaceShapeDeformations,System.Single,Microsoft.Kinect.Face.FaceShapeDeformations,System.Single})
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModel
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
