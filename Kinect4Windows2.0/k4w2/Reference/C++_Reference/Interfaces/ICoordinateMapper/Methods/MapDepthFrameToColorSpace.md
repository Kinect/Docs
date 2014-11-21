ICoordinateMapper::MapDepthFrameToColorSpace Method  
===================================================  

Uses the depth frame data to map the entire frame from depth space to color space. <span id="syntaxSection"></span>

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
HRESULT MapDepthFrameToColorSpace(  
         UINT depthPointCount,  
         const UINT16 *depthFrameData,  
         UINT colorPointCount,  
         ColorSpacePoint *colorSpacePoints  
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

*colorPointCount*    
Type: UINT  
The number of color points.  

*colorSpacePoints*    
Type: ColorSpacePoint  
[out] The array of mapped color points that will be filled.  

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
TOCTitle : MapDepthFrameToColorSpace Method
RLTitle : ICoordinateMapper::MapDepthFrameToColorSpace Method
KeywordK : MapDepthFrameToColorSpace method
KeywordK : ICoordinateMapper::MapDepthFrameToColorSpace method
KeywordF : ICoordinateMapper::MapDepthFrameToColorSpace
KeywordF : MapDepthFrameToColorSpace
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthFrameToColorSpace(UINT,UINT16,UINT,ColorSpacePoint@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthFrameToColorSpace(UINT,UINT16,UINT,ColorSpacePoint@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.MapDepthFrameToColorSpace(UINT,UINT16,UINT,ColorSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::MapDepthFrameToColorSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
