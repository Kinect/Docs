NuiFusionDepthToDepthFloatFrame  
===============================  

Converts the specified array of Kinect depth pixels to a NUI\_FUSION\_IMAGE\_FRAME object representing a depth float frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionDepthToDepthFloatFrame(  
         const UINT16 *pDepthImageData,  
         UINT depthImageDataWidth,  
         UINT depthImageDataHeight,  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         FLOAT minDepthClip,  
         FLOAT maxDepthClip,  
         BOOL mirrorDepth  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthImageData*    
Type: UINT16  
[in] The array of Kinect depth pixels in unsigned short format to convert. This data must have the same pixel resolution as the depthFloatFrame parameter.  

*depthImageDataWidth*    
Type: UINT  
[in] The width of the depth image data.  

*depthImageDataHeight*    
Type: UINT  
[in] The height of the depth image data.  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] The genereated NUI\_FUSION\_IMAGE\_FRAME.  

*minDepthClip*    
Type: FLOAT  
[in] The minimum depth threshold, meters. Values below this threshold will be set to zero.  

*maxDepthClip*    
Type: FLOAT  
[in] The maximum depth threshold, in meters. Values above this threshold will be set to 1,000.  

*mirrorDepth*    
Type: BOOL  
[in] Specify true to mirror the depth values. Specify false so the image appears correct if viewing the Kinect sensor from behind.  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT FUSIONAPI  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusiondepthprocessor.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NuiFusionDepthToDepthFloatFrame
RLTitle : NuiFusionDepthToDepthFloatFrame
KeywordK : NuiFusionDepthToDepthFloatFrame
KeywordF : NuiFusionDepthToDepthFloatFrame
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame(UINT16,UINT,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame(UINT16,UINT,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame(UINT16,UINT,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
