ICoordinateMapper::MapCameraPointsToColorSpace Method  
=====================================================  

Maps an array of points from camera space to color space. <span id="syntaxSection"></span>

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
HRESULT MapCameraPointsToColorSpace(  
         UINT cameraPointCount,  
         const CameraSpacePoint *cameraPoints,  
         UINT colorPointCount,  
         ColorSpacePoint *colorPoints  
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

*colorPointCount*    
Type: UINT  
The number of color points.  

*colorPoints*    
Type: ColorSpacePoint  
[out] The points mapped to color space that will be filled.  

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
TOCTitle : MapCameraPointsToColorSpace Method
RLTitle : ICoordinateMapper::MapCameraPointsToColorSpace Method
KeywordK : MapCameraPointsToColorSpace method
KeywordK : ICoordinateMapper::MapCameraPointsToColorSpace method
KeywordF : ICoordinateMapper::MapCameraPointsToColorSpace
KeywordF : MapCameraPointsToColorSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointsToColorSpace(UINT,CameraSpacePoint,UINT,ColorSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointsToColorSpace(UINT,CameraSpacePoint,UINT,ColorSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointsToColorSpace(UINT,CameraSpacePoint,UINT,ColorSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapCameraPointsToColorSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
