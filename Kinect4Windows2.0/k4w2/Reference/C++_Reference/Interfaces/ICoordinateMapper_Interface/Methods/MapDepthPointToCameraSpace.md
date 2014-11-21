ICoordinateMapper::MapDepthPointToCameraSpace Method  
====================================================  

Maps a point and depth from depth space to camera space. <span id="syntaxSection"></span>

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
HRESULT MapDepthPointToCameraSpace(  
         DepthSpacePoint depthPoint,  
         UINT16 depth,  
         CameraSpacePoint *cameraPoint  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthPoint*    
Type: DepthSpacePoint  
The point to map from depth space.  

*depth*    
Type: UINT16  
The depths of the points in depth space.  

*cameraPoint*    
Type: CameraSpacePoint  
[out] The point mapped to camera space.  

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
TOCTitle : MapDepthPointToCameraSpace Method
RLTitle : ICoordinateMapper::MapDepthPointToCameraSpace Method
KeywordK : MapDepthPointToCameraSpace method
KeywordK : ICoordinateMapper::MapDepthPointToCameraSpace method
KeywordF : ICoordinateMapper::MapDepthPointToCameraSpace
KeywordF : MapDepthPointToCameraSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthPointToCameraSpace(DepthSpacePoint,UINT16,CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthPointToCameraSpace(DepthSpacePoint,UINT16,CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthPointToCameraSpace(DepthSpacePoint,UINT16,CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapDepthPointToCameraSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
