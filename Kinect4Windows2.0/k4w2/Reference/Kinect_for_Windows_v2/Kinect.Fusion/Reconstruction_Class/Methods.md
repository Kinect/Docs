Reconstruction Methods  
======================  

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
<td align="left"><a href="Methods/AlignDepthFloatFrameToReco.md">AlignDepthFloatFrameToReconstruction</a></td>
<td align="left">Aligns a depth float image to the reconstruction volume to calculate the new camera pose.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/AlignPointClouds_Method.md">AlignPointClouds</a></td>
<td align="left">Aligns two sets of overlapping oriented point clouds and calculates the camera's relative pose.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/CalculateMesh_Method.md">CalculateMesh</a></td>
<td align="left">Exports a polygon mesh of the zero-crossing dense surfaces from the reconstruction volume with per-vertex color.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/CalculatePointCloud_Method.md">CalculatePointCloud</a></td>
<td align="left">Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose and color visualization image.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/CalculatePointCloudAndDepth.md">CalculatePointCloudAndDepth</a></td>
<td align="left">Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose, color visualization image, and the depth to the surface.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/DepthToDepthFloatFrame.md">DepthToDepthFloatFrame</a></td>
<td align="left">Converts the specified buffer of Kinect depth pixels to a <a href="../DepthFloatFrame_Class.md">DepthFloatFrame</a> object.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/ExportVolumeBlock_Method.md">ExportVolumeBlock</a></td>
<td align="left">Exports a part or all of the reconstruction volume as a buffer of shorts.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/GetCurrentWorldToCameraTra.md">GetCurrentWorldToCameraTransform</a></td>
<td align="left">Retrieves the current internal world-to-camera transform (camera view pose).</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/GetCurrentWorldToVolumeTra.md">GetCurrentWorldToVolumeTransform</a></td>
<td align="left">Get current internal world-to-volume transform.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/ImportVolumeBlock_Method.md">ImportVolumeBlock</a></td>
<td align="left">Imports a reconstruction volume as a short array.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/IntegrateFrame_Method.md">IntegrateFrame</a></td>
<td align="left">Integrates depth float data into the reconstruction volume from the passed camera pose.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/ProcessFrame_Method.md">ProcessFrame</a></td>
<td align="left">A high-level function to process a depth frame through the Kinect Fusion pipeline.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/ResetReconstruction_Method.md">ResetReconstruction</a></td>
<td align="left">Clear the reconstruction volume, and set a world-to-camera transform (camera view pose) and a world-to-volume transform.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/SetAlignDepthFloatToRecons.md">SetAlignDepthFloatToReconstructionReferenceFrame</a></td>
<td align="left">Sets a reference depth frame that is used internally to help with tracking when calling the <a href="Methods/AlignDepthFloatFrameToReco.md">AlignDepthFloatFrameToReconstruction</a> method to calculate a new camera pose.  
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">You should call this method only if you are not using the default tracking behavior of Kinect Fusion.</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/SmoothDepthFloatFrame_Method.md">SmoothDepthFloatFrame</a></td>
<td align="left">Spatially smoothes a depth float image frame using edge-preserving filtering.</td>
</tr>
</tbody>
</table>

<span id="ID4EI"></span>

See also  
========  

<span id="ID4EK"></span>
#### Reference  

[Reconstruction Class](../Reconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Reconstruction Methods
RLTitle : Reconstruction Methods
KeywordK : Reconstruction class, methods
KeywordA : Methods.T:Microsoft.Kinect.Fusion.Reconstruction
AssetID : Methods.T:Microsoft.Kinect.Fusion.Reconstruction
Locale : en-us
CommunityContent : 1
TargetOS : Windows
TopicType : kbSyntax
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
