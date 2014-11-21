ICoordinateMapper::MapColorFrameToCameraSpace Method  
====================================================  

Uses the color frame data to map the entire frame from color space to camera space. <span id="syntaxSection"></span>

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
HRESULT MapColorFrameToCameraSpace(  
         UINT depthDataPointCount,  
         const UINT16 *depthFrameData,  
         UINT cameraPointCount,  
         CameraSpacePoint *cameraSpacePoints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthDataPointCount*    
Type: UINT  
The number of depth data points.  

*depthFrameData*    
Type: UINT16  
[in] The full image data from a depth frame.  

*cameraPointCount*    
Type: UINT  
The number of camera points.  

*cameraSpacePoints*    
Type: CameraSpacePoint  
[out] The array of mapped camera points that will be filled.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The cameraPoints array should be the same size of the number of color frame pixels.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapColorFrameToCameraSpace Method
RLTitle : ICoordinateMapper::MapColorFrameToCameraSpace Method
KeywordK : MapColorFrameToCameraSpace method
KeywordK : ICoordinateMapper::MapColorFrameToCameraSpace method
KeywordF : ICoordinateMapper::MapColorFrameToCameraSpace
KeywordF : MapColorFrameToCameraSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapColorFrameToCameraSpace(UINT,UINT16,UINT,CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapColorFrameToCameraSpace(UINT,UINT16,UINT,CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapColorFrameToCameraSpace(UINT,UINT16,UINT,CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapColorFrameToCameraSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
