INuiFusionReconstruction::IntegrateFrame Method  
===============================================  

Integrates depth float data and color data into the reconstruction volume from the specified camera pose. <span id="syntaxSection"></span>

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
HRESULT IntegrateFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         USHORT maxIntegrationWeight,  
         const Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
The depth float frame to be integrated.  

*maxIntegrationWeight*    
Type: USHORT  
A parameter to control the temporal smoothing of depth integration. The minimum value is one. Lower values have more noisy representations, but are suitable for more dynamic environments because moving objects integrate and disintegrate faster. Higher values integrate objects more slowly, but provide finer detail with less noise.  

*pWorldToCameraTransform*    
Type: Matrix4  
The camera pose. This is usually the camera pose result from the most recent call to the [AlignPointClouds](AlignPointClouds_Method.md) or [AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md) method.  

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
TOCTitle : IntegrateFrame Method
RLTitle : INuiFusionReconstruction::IntegrateFrame Method
KeywordK : IntegrateFrame method
KeywordK : INuiFusionReconstruction::IntegrateFrame method
KeywordF : INuiFusionReconstruction::IntegrateFrame
KeywordF : IntegrateFrame
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,USHORT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,USHORT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,USHORT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::IntegrateFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
