CreateFaceModel  
===============  

Creates a face model. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateFaceModel(  
         float scale,  
         UINT32 capacity,  
         float *pDeformations,  
         IFaceModel **ppFaceModel  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*scale*    
Type: float  
The scale of the model.  

*capacity*    
Type: UINT32  
The size of the pDeformations array.  

*pDeformations*    
Type: float  
[in] An array of face deformations.  

*ppFaceModel*    
Type: IFaceModel  
[out] The generated face model.  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

You must pass in an initialized array of float values the first time this method is called. They array must be of size typedef const FaceShapeDeformations\_Count; and each element value should be 0.0f. If you are creating a face model from a previously generated face model, you can use the values returned from the call to IFaceModel::GetFaceShapeDeformations.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CreateFaceModel
RLTitle : CreateFaceModel
KeywordK : CreateFaceModel
KeywordF : CreateFaceModel
KeywordF : Microsoft.Kinect.face.CreateFaceModel(float,UINT32,float,IFaceModel@)
KeywordA : M:Microsoft.Kinect.face.CreateFaceModel(float,UINT32,float,IFaceModel@)
AssetID : M:Microsoft.Kinect.face.CreateFaceModel(float,UINT32,float,IFaceModel@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.CreateFaceModel
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
