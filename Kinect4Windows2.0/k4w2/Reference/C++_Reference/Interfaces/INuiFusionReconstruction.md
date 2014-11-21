INuiFusionReconstruction Interface  
==================================  

Reconstruction encapsulates reconstruction volume creation updating and meshing functions. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface INuiFusionReconstruction : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionReconstruction** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/AlignDepthFloatToReconstru.md">AlignDepthFloatToReconstruction</a></td>
<td align="left">Aligns a depth float image to the reconstruction volume to calculate the new camera pose.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/AlignPointClouds_Method.md">AlignPointClouds</a></td>
<td align="left">Aligns two sets of overlapping oriented point clouds and calculates the camera's relative pose.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/CalculateMesh_Method.md">CalculateMesh</a></td>
<td align="left">Exports a polygon mesh of the zero-crossing dense surfaces from the reconstruction volume with per-vertex color.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/CalculatePointCloud_Method.md">CalculatePointCloud</a></td>
<td align="left">Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose and color visualization image.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/CalculatePointCloudAndDepth.md">CalculatePointCloudAndDepth</a></td>
<td align="left">Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose, color visualization image, and the depth to the surface.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/DepthToDepthFloatFrame.md">DepthToDepthFloatFrame</a></td>
<td align="left">Converts the specified array of Kinect depth pixels to a NUI_FUSION_IMAGE_FRAME object representing a depth float frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/ExportVolumeBlock_Method.md">ExportVolumeBlock</a></td>
<td align="left">Exports a part or all of the reconstruction volume as a short array.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/GetCurrentWorldToCameraTra.md">GetCurrentWorldToCameraTransform</a></td>
<td align="left">Retrieves the current internal world-to-camera transform (camera view pose).</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/GetCurrentWorldToVolumeTra.md">GetCurrentWorldToVolumeTransform</a></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/ImportVolumeBlock_Method.md">ImportVolumeBlock</a></td>
<td align="left">Imports a reconstruction volume as a buffer of shorts, with color as an integer buffer.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/IntegrateFrame_Method.md">IntegrateFrame</a></td>
<td align="left">Integrates depth float data and color data into the reconstruction volume from the specified camera pose.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/ProcessFrame_Method.md">ProcessFrame</a></td>
<td align="left">Processes the specified depth frame and color frame through the Kinect Fusion pipeline.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/ResetReconstruction_Method.md">ResetReconstruction</a></td>
<td align="left">Clears the reconstruction volume and sets a new world-to-camera transform (camera view pose).</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/SetAlignDepthFloatToRecons.md">SetAlignDepthFloatToReconstructionReferenceFrame</a></td>
<td align="left">Sets a reference depth frame that is used internally to help with tracking when calling the <a href="INuiFusionReconstruction/Methods/AlignDepthFloatToReconstru.md">AlignDepthFloatToReconstruction</a> method to calculate a new camera pose.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/SmoothDepthFloatFrame_Method.md">SmoothDepthFloatFrame</a></td>
<td align="left">Spatially smoothes a depth float image frame using edge-preserving filtering.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionReconstruction Interface
RLTitle : INuiFusionReconstruction Interface
KeywordK : INuiFusionReconstruction interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionReconstruction
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
KeywordA : T:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
AssetID : T:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
