INuiFusionColorReconstruction::CalculateMesh Method  
===================================================  

Exports a polygon mesh of the zero-crossing dense surfaces from the reconstruction volume with per-vertex color. <span id="syntaxSection"></span>

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
HRESULT CalculateMesh(  
         UINT voxelStep,  
         INuiFusionColorMesh **ppMesh  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*voxelStep*    
Type: UINT  
 The step value in voxels for sampling points to use in the volume when exporting a mesh, which determines the final resolution of the mesh. Use higher values for lower resolution meshes. This value must be greater than zero and smaller than the smallest volume axis voxel resolution. To mesh the volume at its full resolution, use a step value of one.  

| ![](../../../../../../resources/note.gif)Note                                                                                        |
|--------------------------------------------------------------------------------------------------------------------------------------|
| Any value higher than one for this parameter runs the risk of missing zero crossings, and hence missing surfaces or surface details. |

*ppMesh*    
Type: INuiFusionColorMesh  
The calculated mesh.  

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
TOCTitle : CalculateMesh Method
RLTitle : INuiFusionColorReconstruction::CalculateMesh Method
KeywordK : CalculateMesh method
KeywordK : INuiFusionColorReconstruction::CalculateMesh method
KeywordF : INuiFusionColorReconstruction::CalculateMesh
KeywordF : CalculateMesh
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculateMesh(UINT,INuiFusionColorMesh)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculateMesh(UINT,INuiFusionColorMesh)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculateMesh(UINT,INuiFusionColorMesh)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::CalculateMesh
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
