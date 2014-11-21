INuiFusionColorReconstruction::AlignPointClouds Method  
======================================================  

Aligns two sets of overlapping oriented point clouds and calculates the camera's relative pose. <span id="syntaxSection"></span>

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
HRESULT AlignPointClouds(  
         const NUI_FUSION_IMAGE_FRAME *pReferencePointCloudFrame,  
         const NUI_FUSION_IMAGE_FRAME *pObservedPointCloudFrame,  
         USHORT maxAlignIterationCount,  
         const NUI_FUSION_IMAGE_FRAME *pDeltaFromReferenceFrame,  
         FLOAT *pAlignmentEnergy,  
         Matrix4 *pReferenceToObservedTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pReferencePointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
A reference point cloud frame. This image must be the same size and have the same camera parameters as the pObservedPointCloudFrame parameter.  

*pObservedPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
An observed point cloud frame. This image must be the same size and have the same camera parameters as the pReferencePointCloudFrame parameter.  

*maxAlignIterationCount*    
Type: USHORT  
The number of iterations to run.  

*pDeltaFromReferenceFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
 Optional pre-allocated color image frame that receives color-coded data from the camera tracking. This image can be used as input to additional vision algorithms, such as object segmentation. If specified, this image must be the same size and have the same camera parameters as the pReferencePointCloudFrame and pObservedPointCloudFrame parameters. If you do not need this output image, specify null.  

The values in the received image vary depending on whether the pixel was a valid pixel used in tracking (inlier) or failed in different tests (outlier). Inliers are color shaded depending on the residual energy at that point. Higher discrepancy between vertices is indicated by more saturated colors. Less discrepancy between vertices (less information at that pixel) is indicated by less saturated colors (that is, more white). If the pixel is an outlier, it will receive one of the values listed in the following table.  

| Value      | Description                                                                                                                                                |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0xFF000000 | The input vertex was invalid (for example, a vertex with an input depth of zero), or the vertex had no correspondences between the two point cloud images. |
| 0xFF008000 | The outlier vertices were rejected due to too large a distance between vertices.                                                                           |
| 0xFF800000 | The outlier vertices were rejected due to too large a difference in normal angle between the point clouds.                                                 |

*pAlignmentEnergy*    
Type: FLOAT  
The threshold in the range [0.0f, 1.0f] that describes how well the observed frame aligns to the model with the calculated pose (mean distance between matching points in the point clouds).  

*pReferenceToObservedTransform*    
Type: Matrix4  
Gets the world-to-camera transform (camera view pose) associated with the alignment result.  

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
TOCTitle : AlignPointClouds Method
RLTitle : INuiFusionColorReconstruction::AlignPointClouds Method
KeywordK : AlignPointClouds method
KeywordK : INuiFusionColorReconstruction::AlignPointClouds method
KeywordF : INuiFusionColorReconstruction::AlignPointClouds
KeywordF : AlignPointClouds
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.AlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.AlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.AlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::AlignPointClouds
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
