NuiFusionShadePointCloud  
========================  

Produces two shaded images from the point cloud frame, based on point position and surface normal. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionShadePointCloud(  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame,  
         const Matrix4 *pWorldToCameraTransform,  
         const Matrix4 *pWorldToBGRTransform,  
         const NUI_FUSION_IMAGE_FRAME *pShadedSurfaceFrame,  
         const NUI_FUSION_IMAGE_FRAME *pShadedSurfaceNormalsFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] The point cloud frame to shade.  

*pWorldToCameraTransform*    
Type: Matrix4  
[in] The transform used to determine the perspective of the shaded point cloud relative to the world. This affects the application of the worldToRGBTramsform to the point cloud. To achieve consistent results, this should match the world-to-camera transform that was used to create the point cloud frame.  

*pWorldToBGRTransform*    
Type: Matrix4  
[in, optional] The transform that defines a mapping from position to RGB color space. The X, Y, Z components of the point positions transformed by this matrix are used as the R, G, B values in the rendered frame.  

*pShadedSurfaceFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in, optional] A color image frame that receives the shaded frame which includes lighting based on the surface normal.  

*pShadedSurfaceNormalsFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in, optional] A color image frame that receives the shaded frame.  

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
TOCTitle : NuiFusionShadePointCloud
RLTitle : NuiFusionShadePointCloud
KeywordK : NuiFusionShadePointCloud
KeywordF : NuiFusionShadePointCloud
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud(NUI_FUSION_IMAGE_FRAME,Matrix4,Matrix4,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud(NUI_FUSION_IMAGE_FRAME,Matrix4,Matrix4,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud(NUI_FUSION_IMAGE_FRAME,Matrix4,Matrix4,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
