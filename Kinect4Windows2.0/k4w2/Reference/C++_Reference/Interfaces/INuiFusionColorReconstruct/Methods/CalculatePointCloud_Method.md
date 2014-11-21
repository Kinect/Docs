INuiFusionColorReconstruction::CalculatePointCloud Method  
=========================================================  

Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose and color visualization image. <span id="syntaxSection"></span>

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
HRESULT CalculatePointCloud(  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame,  
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
TOCTitle : CalculatePointCloud Method
RLTitle : INuiFusionColorReconstruction::CalculatePointCloud Method
KeywordK : CalculatePointCloud method
KeywordK : INuiFusionColorReconstruction::CalculatePointCloud method
KeywordF : INuiFusionColorReconstruction::CalculatePointCloud
KeywordF : CalculatePointCloud
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::CalculatePointCloud
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
