INuiFusionColorReconstruction::SmoothDepthFloatFrame Method  
===========================================================  

Spatially smoothes a depth float image frame using edge-preserving filtering. <span id="syntaxSection"></span>

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
HRESULT SmoothDepthFloatFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pSmoothDepthFloatFrame,  
         UINT kernelWidth,  
         FLOAT distanceThreshold  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
A source depth float frame.  

*pSmoothDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
A depth float frame that receives the smoothed depth frame.  

*kernelWidth*    
Type: UINT  
 The smoothing kernel width. The valid values are listed in the following table.  

| *kernelWidth value* | Smoothing kernel block size |
|---------------------|-----------------------------|
| 1                   | 3×3                         |
| 2                   | 5×5                         |
| 3                   | 7×7                         |

*distanceThreshold*    
Type: FLOAT  
A source depth float frame.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SmoothDepthFloatFrame Method
RLTitle : INuiFusionColorReconstruction::SmoothDepthFloatFrame Method
KeywordK : SmoothDepthFloatFrame method
KeywordK : INuiFusionColorReconstruction::SmoothDepthFloatFrame method
KeywordF : INuiFusionColorReconstruction::SmoothDepthFloatFrame
KeywordF : SmoothDepthFloatFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SmoothDepthFloatFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,UINT,FLOAT)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SmoothDepthFloatFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,UINT,FLOAT)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SmoothDepthFloatFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,UINT,FLOAT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::SmoothDepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
