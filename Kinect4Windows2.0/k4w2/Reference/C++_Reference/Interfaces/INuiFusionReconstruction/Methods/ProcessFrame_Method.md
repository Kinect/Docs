INuiFusionReconstruction::ProcessFrame Method  
=============================================  

Processes the specified depth frame and color frame through the Kinect Fusion pipeline. <span id="syntaxSection"></span>

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
HRESULT ProcessFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         USHORT maxAlignIterationCount,  
         USHORT maxIntegrationWeight,  
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
The depth float frame to be processed. The maximum resolution of this frame is 640×480.  

*maxAlignIterationCount*    
Type: USHORT  
The maximum number of iterations of the algorithm to run. The minimum value is one. Using only a small number of iterations will have a faster run time, but the algorithm may not converge to the correct transformation.  

*maxIntegrationWeight*    
Type: USHORT  
A parameter to control the temporal smoothing of depth integration. The minimum value is one. Lower values have more noisy representations, but are suitable for more dynamic environments because moving objects integrate and disintegrate faster. Higher values integrate objects more slowly, but provide finer detail with less noise.  

*pAlignmentEnergy*    
Type: FLOAT  
The Gets threshold in the range [0.0f, 1.0f] that describes how well the observed frame aligns to the model with the calculated pose (mean distance between matching points in the point clouds).  

*pWorldToCameraTransform*    
Type: Matrix4  
The best guess at the current camera pose. This is usually the camera pose result from the most recent call to the [AlignPointClouds](AlignPointClouds_Method.md) or [AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md) method.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

This method is equivalent to calling the [AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md) and [IntegrateFrame](IntegrateFrame_Method.md) methods on the specified depth frame. You can call these low-level methods individually to have more control over the operation, but calling ProcessFrame will complete faster due to the integrated nature of the calls.  
| ![](../../../../../../resources/note.gif)Note                                                                                                                      |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| If a tracking error occurs during the AlignDepthFloatToReconstruction call, no depth data integration will be performed and the camera pose will remain unchanged. |

If you need a visible output image of the reconstruction, call the [CalculatePointCloud](CalculatePointCloud_Method.md) method and then call the [NuiFusionShadePointCloud](../../../Functions/NuiFusionShadePointCloud.md) function.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : INuiFusionReconstruction::ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : INuiFusionReconstruction::ProcessFrame method
KeywordF : INuiFusionReconstruction::ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::ProcessFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
