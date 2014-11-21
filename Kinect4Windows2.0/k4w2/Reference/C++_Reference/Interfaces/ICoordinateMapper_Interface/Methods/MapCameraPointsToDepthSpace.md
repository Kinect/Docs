ICoordinateMapper::MapCameraPointsToDepthSpace Method  
=====================================================  

Maps an array of points from camera space to depth space. <span id="syntaxSection"></span>

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
HRESULT MapCameraPointsToDepthSpace(  
         UINT cameraPointCount,  
         const CameraSpacePoint *cameraPoints,  
         UINT depthPointCount,  
         DepthSpacePoint *depthPoints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cameraPointCount*    
Type: UINT  
The number of camera points.  

*cameraPoints*    
Type: CameraSpacePoint  
[in] The points to map from camera space.  

*depthPointCount*    
Type: UINT  
The number of depth points.  

*depthPoints*    
Type: DepthSpacePoint  
[out] The points mapped to depth space that will be filled.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapCameraPointsToDepthSpace Method
RLTitle : ICoordinateMapper::MapCameraPointsToDepthSpace Method
KeywordK : MapCameraPointsToDepthSpace method
KeywordK : ICoordinateMapper::MapCameraPointsToDepthSpace method
KeywordF : ICoordinateMapper::MapCameraPointsToDepthSpace
KeywordF : MapCameraPointsToDepthSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointsToDepthSpace(UINT,CameraSpacePoint,UINT,DepthSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointsToDepthSpace(UINT,CameraSpacePoint,UINT,DepthSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointsToDepthSpace(UINT,CameraSpacePoint,UINT,DepthSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapCameraPointsToDepthSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
