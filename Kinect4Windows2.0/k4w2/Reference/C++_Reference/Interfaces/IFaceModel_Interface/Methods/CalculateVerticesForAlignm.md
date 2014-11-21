IFaceModel::CalculateVerticesForAlignment Method  
================================================  

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
HRESULT CalculateVerticesForAlignment(  
         IFaceAlignment *faceAlignment,  
         UINT capacity,  
         CameraSpacePoint *vertices  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceAlignment*    
Type: IFaceAlignment  
The face alignment.  

*capacity*    
Type: UINT  
The size of the vertices array.  

*vertices*    
Type: CameraSpacePoint  
[out] The array in which the vertices will be stored.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

There are 1347 vertices for the HD Face model. The array should be initialized with that amount of elements.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculateVerticesForAlignment Method
RLTitle : IFaceModel::CalculateVerticesForAlignment Method
KeywordK : CalculateVerticesForAlignment method
KeywordK : IFaceModel::CalculateVerticesForAlignment method
KeywordF : IFaceModel::CalculateVerticesForAlignment
KeywordF : CalculateVerticesForAlignment
KeywordF : Microsoft.Kinect.face.IFaceModel.CalculateVerticesForAlignment(IFaceAlignment,UINT,CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.face.IFaceModel.CalculateVerticesForAlignment(IFaceAlignment,UINT,CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.face.IFaceModel.CalculateVerticesForAlignment(IFaceAlignment,UINT,CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModel::CalculateVerticesForAlignment
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
