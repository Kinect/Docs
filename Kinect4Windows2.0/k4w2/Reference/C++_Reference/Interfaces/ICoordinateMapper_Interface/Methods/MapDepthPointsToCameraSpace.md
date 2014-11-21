ICoordinateMapper::MapDepthPointsToCameraSpace Method  
=====================================================  

Maps an array of points and depths from depth space to camera space. <span id="syntaxSection"></span>

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
HRESULT MapDepthPointsToCameraSpace(  
         UINT depthPointCount,  
         const DepthSpacePoint *depthPoints,  
         UINT depthCount,  
         const UINT16 *depths,  
         UINT cameraPointCount,  
         CameraSpacePoint *cameraPoints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthPointCount*    
Type: UINT  
The number of depth points.  

*depthPoints*    
Type: DepthSpacePoint  
[in] The points to map from depth space.  

*depthCount*    
Type: UINT  
The number of depths.  

*depths*    
Type: UINT16  
[in] The depths of the points in depth space.  

*cameraPointCount*    
Type: UINT  
The number of camera points.  

*cameraPoints*    
Type: CameraSpacePoint  
[out] The points mapped to camera space that will be filled.  

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
TOCTitle : MapDepthPointsToCameraSpace Method
RLTitle : ICoordinateMapper::MapDepthPointsToCameraSpace Method
KeywordK : MapDepthPointsToCameraSpace method
KeywordK : ICoordinateMapper::MapDepthPointsToCameraSpace method
KeywordF : ICoordinateMapper::MapDepthPointsToCameraSpace
KeywordF : MapDepthPointsToCameraSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthPointsToCameraSpace(UINT,DepthSpacePoint,UINT,UINT16,UINT,CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthPointsToCameraSpace(UINT,DepthSpacePoint,UINT,UINT16,UINT,CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthPointsToCameraSpace(UINT,DepthSpacePoint,UINT,UINT16,UINT,CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapDepthPointsToCameraSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
