INuiFusionReconstruction::GetCurrentWorldToVolumeTransform Method  
=================================================================  

<span id="syntaxSection"></span>

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
HRESULT GetCurrentWorldToVolumeTransform(  
         Matrix4 *pWorldToVolumeTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pWorldToVolumeTransform*    
Type: Matrix4  
 The current world-to-volume transform. This is a similarity transformation that converts world coordinates to volume coordinates.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

A right handed coordinate system is used, with the origin of the volume (that is, voxel 0,0,0) at the top left of the front plane of the cube. Similar to bitmap images with top left origin, +X is to the right, +Y down, and +Z is forward from the origin into the reconstruction volume.  

The default transformation is a combination of translation in x-axis and y-axis to locate the world origin at the center of the front face of the reconstruction volume cube, and scaling by the [VoxelsPerMeter](../../../Structures/NUI_FUSION_RECONSTRUCTION.md) field to convert from the world coordinate system to volume voxel indices.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetCurrentWorldToVolumeTransform Method
RLTitle : INuiFusionReconstruction::GetCurrentWorldToVolumeTransform Method
KeywordK : GetCurrentWorldToVolumeTransform method
KeywordK : INuiFusionReconstruction::GetCurrentWorldToVolumeTransform method
KeywordF : INuiFusionReconstruction::GetCurrentWorldToVolumeTransform
KeywordF : GetCurrentWorldToVolumeTransform
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.GetCurrentWorldToVolumeTransform(Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.GetCurrentWorldToVolumeTransform(Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.GetCurrentWorldToVolumeTransform(Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::GetCurrentWorldToVolumeTransform
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
