ICoordinateMapper::MapDepthFrameToCameraSpace Method  
====================================================  

Uses the depth frame data to map the entire frame from depth space to camera space. <span id="syntaxSection"></span>

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
HRESULT MapDepthFrameToCameraSpace(  
         UINT depthPointCount,  
         const UINT16 *depthFrameData,  
         UINT cameraPointCount,  
         CameraSpacePoint *cameraSpacePoints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthPointCount*    
Type: UINT  
The number of depth points.  

*depthFrameData*    
Type: UINT16  
[in] The full image data from a depth frame.  

*cameraPointCount*    
Type: UINT  
The number of camera points.  

*cameraSpacePoints*    
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
TOCTitle : MapDepthFrameToCameraSpace Method
RLTitle : ICoordinateMapper::MapDepthFrameToCameraSpace Method
KeywordK : MapDepthFrameToCameraSpace method
KeywordK : ICoordinateMapper::MapDepthFrameToCameraSpace method
KeywordF : ICoordinateMapper::MapDepthFrameToCameraSpace
KeywordF : MapDepthFrameToCameraSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthFrameToCameraSpace(UINT,UINT16,UINT,CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthFrameToCameraSpace(UINT,UINT16,UINT,CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthFrameToCameraSpace(UINT,UINT16,UINT,CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapDepthFrameToCameraSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
