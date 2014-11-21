ICoordinateMapper::GetDepthCameraIntrinsics Method  
==================================================  

Returns the calibration data for the depth camera. <span id="syntaxSection"></span>

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
HRESULT GetDepthCameraIntrinsics(  
         CameraIntrinsics *cameraIntrinsics  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cameraIntrinsics*    
Type: CameraIntrinsics  
[out] The calibration data for the depth camera.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetDepthCameraIntrinsics Method
RLTitle : ICoordinateMapper::GetDepthCameraIntrinsics Method
KeywordK : GetDepthCameraIntrinsics method
KeywordK : ICoordinateMapper::GetDepthCameraIntrinsics method
KeywordF : ICoordinateMapper::GetDepthCameraIntrinsics
KeywordF : GetDepthCameraIntrinsics
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.GetDepthCameraIntrinsics(CameraIntrinsics@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.GetDepthCameraIntrinsics(CameraIntrinsics@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.GetDepthCameraIntrinsics(CameraIntrinsics@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::GetDepthCameraIntrinsics
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
