INuiFusionColorReconstruction::ProcessFrame Method  
==================================================  

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
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         USHORT maxAlignIterationCount,  
         USHORT maxIntegrationWeight,  
         FLOAT maxColorIntegrationAngle,  
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

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
The color frame to be processed. The maximum resolution of this frame is 640×480.  

*maxAlignIterationCount*    
Type: USHORT  
The maximum number of iterations of the algorithm to run. The minimum value is one. Using only a small number of iterations will have a faster run time, but the algorithm may not converge to the correct transformation.  

*maxIntegrationWeight*    
Type: USHORT  
A parameter to control the temporal smoothing of depth integration. The minimum value is one. Lower values have more noisy representations, but are suitable for more dynamic environments because moving objects integrate and disintegrate faster. Higher values integrate objects more slowly, but provide finer detail with less noise.  

*maxColorIntegrationAngle*    
Type: FLOAT  
 Angle with respect to the surface normal over which color will be integrated, in degrees. The useful range of values for this parameter is [0.0f, 90.0f]. You can use this parameter to integrate color only when the Kinect sensor is nearly parallel with the surface (that is, the camera direction of view is perpendicular to the surface), or within a specified angle from the surface normal direction.  

This angle relative to this normal direction vector describes the acceptance half angle; for example, a +/- 90 degree acceptance angle in all directions (that is, a 180 degree hemisphere) relative to the normal integrates color in any orientation of the sensor towards the front of the surface, even when parallel to the surface. An acceptance angle of zero integrates color only directly along a single ray exactly perpendicular to the surface.  

Setting this value has a cost at run-time. However, not setting this value causes this method to integrate color from any angle over all voxels along camera rays around the zero crossing surface region in the volume, which can cause thin structures to have the same color on both sides.  

*pAlignmentEnergy*    
Type: FLOAT  
The threshold in the range [0.0f, 1.0f] that describes how well the observed frame aligns to the model with the calculated pose (mean distance between matching points in the point clouds).  

*pWorldToCameraTransform*    
Type: Matrix4  
The best guess at the current camera pose. This is usually the camera pose result from the most recent call to the [AlignPointClouds](AlignPointClouds_Method.md) or [AlignDepthFloatToReconstruction](AlignDepthFloatToReconst.md) method.  

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
TOCTitle : ProcessFrame Method
RLTitle : INuiFusionColorReconstruction::ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : INuiFusionColorReconstruction::ProcessFrame method
KeywordF : INuiFusionColorReconstruction::ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::ProcessFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
