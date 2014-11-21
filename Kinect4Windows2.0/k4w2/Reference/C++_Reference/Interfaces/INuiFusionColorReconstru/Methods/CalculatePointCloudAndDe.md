INuiFusionColorReconstruction::CalculatePointCloudAndDepth Method  
=================================================================  

Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose, color visualization image, and the depth to the surface. <span id="syntaxSection"></span>

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
HRESULT CalculatePointCloudAndDepth(  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame,  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         const Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
 The pre-allocated point cloud frame, to be filled by raycasting into the reconstruction volume. This point cloud can be used as a reference frame in the next call to the [AlignPointClouds](AlignPointClouds_Method.md) method, or passed to the [NuiFusionShadePointCloud](../../../Functions/NuiFusionShadePointCloud.md) function to produce a visible image output.  

The cloud frame can be an arbitrary image size. This allows you to calculate point clouds at the size of your window and then create a visible image by calling the [NuiFusionShadePointCloud](../../../Functions/NuiFusionShadePointCloud.md) function method to render this image. Note that large images are expensive to calculate.  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
 A floating-point depth frame, to be filled with floating-point depths to the raycast surface, in meters. This image must be identical in size and camera parameters to the pPointCloudFrame parameter. You can use this depth image as a reference frame for the [INuiFusionColorReconstruction::AlignDepthFloatToReconstruction Method](AlignDepthFloatToReconst.md) method by calling the [INuiFusionColorReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame Method](SetAlignDepthFloatToReco.md) method to enable a greater range of tracking.  

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
The color frame to fill.  

*pWorldToCameraTransform*    
Type: Matrix4  
The world-to-camera transform (camera pose) to raycast from.  

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
TOCTitle : CalculatePointCloudAndDepth Method
RLTitle : INuiFusionColorReconstruction::CalculatePointCloudAndDepth Method
KeywordK : CalculatePointCloudAndDepth method
KeywordK : INuiFusionColorReconstruction::CalculatePointCloudAndDepth method
KeywordF : INuiFusionColorReconstruction::CalculatePointCloudAndDepth
KeywordF : CalculatePointCloudAndDepth
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloudAndDepth(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloudAndDepth(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloudAndDepth(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::CalculatePointCloudAndDepth
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
