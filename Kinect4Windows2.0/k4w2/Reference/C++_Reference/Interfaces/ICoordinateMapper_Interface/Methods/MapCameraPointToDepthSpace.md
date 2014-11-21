ICoordinateMapper::MapCameraPointToDepthSpace Method  
====================================================  

Maps a point from camera space to depth space. <span id="syntaxSection"></span>

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
HRESULT MapCameraPointToDepthSpace(  
         CameraSpacePoint cameraPoint,  
         DepthSpacePoint *depthPoint  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cameraPoint*    
Type: CameraSpacePoint  
The point to map from camera space.  

*depthPoint*    
Type: DepthSpacePoint  
[out] The point mapped to depth space.  

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
TOCTitle : MapCameraPointToDepthSpace Method
RLTitle : ICoordinateMapper::MapCameraPointToDepthSpace Method
KeywordK : MapCameraPointToDepthSpace method
KeywordK : ICoordinateMapper::MapCameraPointToDepthSpace method
KeywordF : ICoordinateMapper::MapCameraPointToDepthSpace
KeywordF : MapCameraPointToDepthSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointToDepthSpace(CameraSpacePoint,DepthSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointToDepthSpace(CameraSpacePoint,DepthSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointToDepthSpace(CameraSpacePoint,DepthSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapCameraPointToDepthSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
