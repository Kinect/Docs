INuiFusionColorReconstruction::ExportVolumeBlock Method  
=======================================================  

Exports a part or all of the reconstruction volume as a short array. <span id="syntaxSection"></span>

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
HRESULT ExportVolumeBlock(  
         UINT sourceOriginX,  
         UINT sourceOriginY,  
         UINT sourceOriginZ,  
         UINT destinationResolutionX,  
         UINT destinationResolutionY,  
         UINT destinationResolutionZ,  
         UINT voxelStep,  
         UINT cbVolumeBlock,  
         UINT cbColorVolumeBlock,  
         SHORT *pVolumeBlock,  
         INT *pColorVolumeBlock  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sourceOriginX*    
Type: UINT  
The reconstruction volume voxel index in the x-axis from which the extraction should begin. This value must be greater than or equal to zero and less than the reconstruction volume x-axis voxel resolution.  

*sourceOriginY*    
Type: UINT  
The reconstruction volume voxel index in the y-axis from which the extraction should begin. This value must be greater than or equal to zero and less than the reconstruction volume y-axis voxel resolution.  

*sourceOriginZ*    
Type: UINT  
The reconstruction volume voxel index in the z-axis from which the extraction should begin. This value must be greater than or equal to zero and less than the reconstruction volume z-axis voxel resolution.  

*destinationResolutionX*    
Type: UINT  
 The x-axis resolution/width of the new voxel volume to return in the array. This value must be greater than zero and less than or equal to the current volume x-axis voxel resolution. The final count of (sourceOriginX+(destinationResolutionX\*voxelStep) must not be greater than the current reconstruction volume x-axis voxel resolution.  

*destinationResolutionY*    
Type: UINT  
The y-axis resolution/height of the new voxel volume to return in the array. This value must be greater than zero and less than or equal to the current volume y-axis voxel resolution. The final count of (sourceOriginY+(destinationResolutionY\*voxelStep) must not be greater than the current reconstruction volume y-axis voxel resolution.  

*destinationResolutionZ*    
Type: UINT  
The z-axis resolution/depth of the new voxel volume to return in the array. This value must be greater than zero and less than or equal to the current volume z-axis voxel resolution. The final count of (sourceOriginZ+(destinationResolutionZ\*voxelStep) must not be greater than the current reconstruction volume z-axis voxel resolution.  

*voxelStep*    
Type: UINT  
 The step value in integer voxels for sampling points to use in the volume when exporting. This value must be greater than zero and less than the smallest volume axis voxel resolution. To export the volume at its full resolution, use a step value of one. Use higher step values to skip voxels and return the new volume as if there were a lower effective resolution volume. For example, when exporting with a destination resolution of 320^3, setting voxelStep to two would actually cover a 640^3 voxel area (destinationResolution\*voxelStep) in the source reconstruction, but the data returned would skip every other voxel in the original volume.  

| ![](../../../../../../resources/note.gif)Note                                                                                    |
|----------------------------------------------------------------------------------------------------------------------------------|
| Any value higher than one for this value runs the risk of missing zero crossings, and hence missing surfaces or surface details. |

*cbVolumeBlock*    
Type: UINT  
 The size of the pVolumeBlock array.  

*cbColorVolumeBlock*    
Type: UINT  
 The size of the pColorVolumeBlock array.  

*pVolumeBlock*    
Type: SHORT  
 A pre-allocated short array to be filled with volume data. The number of elements in this user array should be allocated as (destinationResolutionX\*destinationResolutionY\*destinationResolutionZ). To access the voxel located at x,y,z use pVolume[z][y][x], or index as a 1D array for a particular voxel(x,y,z) as follows: with pitch = x resolution, slice = (y resolution \* pitch)  

    unsigned int index = (z * slice) + (y * pitch) + x;  

| ![](../../../../../../resources/note.gif)Note                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A right handed coordinate system is used, with the origin of the volume (that is, voxel 0,0,0) at the top left of the front plane of the cube. Similar to bitmap images with top left origin, +X is to the right, +Y down, and +Z is forward from the origin into the reconstruction volume. |

*pColorVolumeBlock*    
Type: INT  
The surface boundary occurs where the trilinearly-interpolated voxel values have a zero crossing (that is, when an interpolation crosses from positive to negative or vice versa). A voxel value of 0x8000 indicates that a voxel is uninitialized and has no valid data associated with it.  

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
TOCTitle : ExportVolumeBlock Method
RLTitle : INuiFusionColorReconstruction::ExportVolumeBlock Method
KeywordK : ExportVolumeBlock method
KeywordK : INuiFusionColorReconstruction::ExportVolumeBlock method
KeywordF : INuiFusionColorReconstruction::ExportVolumeBlock
KeywordF : ExportVolumeBlock
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ExportVolumeBlock(UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,SHORT,INT)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ExportVolumeBlock(UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,SHORT,INT)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ExportVolumeBlock(UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,SHORT,INT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::ExportVolumeBlock
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
