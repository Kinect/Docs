ICoordinateMapper::MapColorFrameToDepthSpace Method  
===================================================  

Uses the depth frame data to map the entire frame from color space to depth space. <span id="syntaxSection"></span>

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
HRESULT MapColorFrameToDepthSpace(  
         UINT depthDataPointCount,  
         const UINT16 *depthFrameData,  
         UINT depthPointCount,  
         DepthSpacePoint *depthSpacePoints  
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

*depthPointCount*    
Type: UINT  
The number of depth points.  

*depthSpacePoints*    
Type: DepthSpacePoint  
[out] The array of mapped depth points that will be filled.  

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
TOCTitle : MapColorFrameToDepthSpace Method
RLTitle : ICoordinateMapper::MapColorFrameToDepthSpace Method
KeywordK : MapColorFrameToDepthSpace method
KeywordK : ICoordinateMapper::MapColorFrameToDepthSpace method
KeywordF : ICoordinateMapper::MapColorFrameToDepthSpace
KeywordF : MapColorFrameToDepthSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapColorFrameToDepthSpace(UINT,UINT16,UINT,DepthSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapColorFrameToDepthSpace(UINT,UINT16,UINT,DepthSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapColorFrameToDepthSpace(UINT,UINT16,UINT,DepthSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapColorFrameToDepthSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
