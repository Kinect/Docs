IFaceFrameResult::GetFacePointsInInfraredSpace Method  
=====================================================  

Gets the face points in infrared space. <span id="syntaxSection"></span>

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
HRESULT GetFacePointsInInfraredSpace(  
         const UINT capacity,  
         PointF *facePoints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[in] The size of the facePoints array.  

*facePoints*    
Type: PointF  
[out] The array in which the face points will be stored.  

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
TOCTitle : GetFacePointsInInfraredSpace Method
RLTitle : IFaceFrameResult::GetFacePointsInInfraredSpace Method
KeywordK : GetFacePointsInInfraredSpace method
KeywordK : IFaceFrameResult::GetFacePointsInInfraredSpace method
KeywordF : IFaceFrameResult::GetFacePointsInInfraredSpace
KeywordF : GetFacePointsInInfraredSpace
KeywordF : Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInInfraredSpace(UINT,PointF@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInInfraredSpace(UINT,PointF@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInInfraredSpace(UINT,PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult::GetFacePointsInInfraredSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
