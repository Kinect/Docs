ICoordinateMapper::MapCameraPointToColorSpace Method  
====================================================  

Maps a point from camera space to color space. <span id="syntaxSection"></span>

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
HRESULT MapCameraPointToColorSpace(  
         CameraSpacePoint cameraPoint,  
         ColorSpacePoint *colorPoint  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cameraPoint*    
Type: CameraSpacePoint  
The point to map from camera space.  

*colorPoint*    
Type: ColorSpacePoint  
[out] The point mapped to color space.  

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
TOCTitle : MapCameraPointToColorSpace Method
RLTitle : ICoordinateMapper::MapCameraPointToColorSpace Method
KeywordK : MapCameraPointToColorSpace method
KeywordK : ICoordinateMapper::MapCameraPointToColorSpace method
KeywordF : ICoordinateMapper::MapCameraPointToColorSpace
KeywordF : MapCameraPointToColorSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointToColorSpace(CameraSpacePoint,ColorSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointToColorSpace(CameraSpacePoint,ColorSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapCameraPointToColorSpace(CameraSpacePoint,ColorSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapCameraPointToColorSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
