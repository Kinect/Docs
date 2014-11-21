INuiFusionReconstruction::ImportVolumeBlock Method  
==================================================  

Imports a reconstruction volume as a buffer of shorts, with color as an integer buffer. <span id="syntaxSection"></span>

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
HRESULT ImportVolumeBlock(  
         UINT cbVolumeBlock,  
         const SHORT *pVolumeBlock  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cbVolumeBlock*    
Type: UINT  
The size of the pVolumeBlock buffer.  

*pVolumeBlock*    
Type: SHORT  
 A pre-allocated short buffer filled with volume data. This buffer must equal the size of the current initialized reconstruction volume. The number of elements in this buffer should be allocated as (destinationResolutionX\*destinationResolutionY\*destinationResolutionZ). To access the voxel located at x,y,z use pVolume[z][y][x], or index as a one-dimensional array for a particular voxel (x,y,z) as follows (with pitch = x resolution, slice = (y resolution \* pitch)). \`  

    unsigned int index = (z * slice)  + (y * pitch) + x;  

| ![](../../../../../../resources/note.gif)Note                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A right handed coordinate system is used, with the origin of the volume (that is, voxel 0,0,0) at the top left of the front plane of the cube. Similar to bitmap images with top left origin, +X is to the right, +Y down, and +Z is forward from the origin into the reconstruction volume. |

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
TOCTitle : ImportVolumeBlock Method
RLTitle : INuiFusionReconstruction::ImportVolumeBlock Method
KeywordK : ImportVolumeBlock method
KeywordK : INuiFusionReconstruction::ImportVolumeBlock method
KeywordF : INuiFusionReconstruction::ImportVolumeBlock
KeywordF : ImportVolumeBlock
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ImportVolumeBlock(UINT,SHORT)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ImportVolumeBlock(UINT,SHORT)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ImportVolumeBlock(UINT,SHORT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::ImportVolumeBlock
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
