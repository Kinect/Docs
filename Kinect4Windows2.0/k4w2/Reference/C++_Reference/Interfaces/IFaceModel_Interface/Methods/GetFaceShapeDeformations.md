IFaceModel::GetFaceShapeDeformations Method  
===========================================  

Gets a collection of face shape deformations. <span id="syntaxSection"></span>

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
HRESULT GetFaceShapeDeformations(  
         UINT32 capacity,  
         float *faceShapeDeformations  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT32  
The size of the faceShapeDeformations array.  

*faceShapeDeformations*    
Type: float  
[out] The array in which the face shape deformations will be stored.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetFaceShapeDeformations Method
RLTitle : IFaceModel::GetFaceShapeDeformations Method
KeywordK : GetFaceShapeDeformations method
KeywordK : IFaceModel::GetFaceShapeDeformations method
KeywordF : IFaceModel::GetFaceShapeDeformations
KeywordF : GetFaceShapeDeformations
KeywordF : Microsoft.Kinect.face.IFaceModel.GetFaceShapeDeformations(UINT32,float@)
KeywordA : M:Microsoft.Kinect.face.IFaceModel.GetFaceShapeDeformations(UINT32,float@)
AssetID : M:Microsoft.Kinect.face.IFaceModel.GetFaceShapeDeformations(UINT32,float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModel::GetFaceShapeDeformations
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
