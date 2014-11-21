INuiFusionReconstruction::AlignDepthFloatToReconstruction Method  
================================================================  

Aligns a depth float image to the reconstruction volume to calculate the new camera pose. <span id="syntaxSection"></span>

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
HRESULT AlignDepthFloatToReconstruction(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         USHORT maxAlignIterationCount,  
         const NUI_FUSION_IMAGE_FRAME *pDeltaFromReferenceFrame,  
         FLOAT *pAlignmentEnergy,  
         const Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
The depth float frame to be processed.  

*maxAlignIterationCount*    
Type: USHORT  
The maximum number of iterations of the algorithm to run. The minimum value is one. Using only a small number of iterations will have a faster run time, but the algorithm may not converge to the correct transformation.  

*pDeltaFromReferenceFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
 A pre-allocated float image frame, to be filled with information about how well each observed pixel aligns with the passed-in reference frame. This could be processed to create a color rendering, or could be used as input to additional vision algorithms such as object segmentation. These residual values are normalized −1 to 1 and represent the alignment cost/energy for each pixel. Larger magnitude values (either positive or negative) represent more discrepancy, and lower values represent less discrepancy or less information at that pixel.  

Note that if valid depth exists, but no reconstruction model exists behind the depth pixels, a value of zero (which indicates perfect alignment) will be returned for that area. In contrast, where no valid depth occurs a value of one will always be returned. Pass null to this parameter if you do not want to use this functionality.  

*pAlignmentEnergy*    
Type: FLOAT  
The threshold in the range [0.0f, 1.0f] that describes how well the observed frame aligns to the model with the calculated pose (mean distance between matching points in the point clouds).  

*pWorldToCameraTransform*    
Type: Matrix4  
The best guess at the current camera pose. This is usually the camera pose result from the most recent call to the [INuiFusionReconstruction::AlignPointClouds Method](AlignPointClouds_Method.md) or [INuiFusionReconstruction::AlignDepthFloatToReconstruction Method]() method.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AlignDepthFloatToReconstruction Method
RLTitle : INuiFusionReconstruction::AlignDepthFloatToReconstruction Method
KeywordK : AlignDepthFloatToReconstruction method
KeywordK : INuiFusionReconstruction::AlignDepthFloatToReconstruction method
KeywordF : INuiFusionReconstruction::AlignDepthFloatToReconstruction
KeywordF : AlignDepthFloatToReconstruction
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.AlignDepthFloatToReconstruction(NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.AlignDepthFloatToReconstruction(NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.AlignDepthFloatToReconstruction(NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::AlignDepthFloatToReconstruction
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
