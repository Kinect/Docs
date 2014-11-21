Reconstruction.CalculatePointCloudAndDepth Method  
=================================================  

Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose, color visualization image, and the depth to the surface. <span id="syntaxSection"></span>

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
void CalculatePointCloudAndDepth(  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> pWorldToCameraTransform,  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>^ pointCloudFrame,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public void CalculatePointCloudAndDepth (  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> pWorldToCameraTransform,  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>pointCloudFrame,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>reconstruction.calculatePointCloudAndDepth(pWorldToCameraTransform, pointCloudFrame, depthFloatFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pWorldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
The world-to-camera transform (camera pose) to raycast from.  

*pointCloudFrame*    
Type: [PointCloudFrame](../../PointCloudFrame_Class.md)  

The pre-allocated point cloud frame, to be filled by raycasting into the reconstruction volume. This point cloud can be used as a reference frame in the next call to the [Reconstruction.AlignPointClouds](AlignPointClouds_Method.md) method, or passed to the [PointCloudFrame.Shade](../../PointCloudFrame_Class/Methods/Shade_Method.md) method to produce a visible image output.  

The cloud frame can be an arbitrary image size. This allows you to calculate point clouds at the size of your window and then create a visible image by calling the **FusionDepthProcessor.ShadePointCloud** method to render this image. Note that large images are expensive to calculate.  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
 A floating-point depth frame, to be filled with floating-point depths to the raycast surface, in meters. This image must be identical in size and camera parameters to the *pointCloudFrame* parameter. You can use this depth image as a reference frame for the [AlignDepthFloatFrameToReconstruction](../../ColorReconstruction_Class/Methods/AlignDepthFloatFrameToRe.md) method to enable a greater range of tracking.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4ECC"></span>

See also  
========  

<span id="ID4EEC"></span>
#### Reference  

[Reconstruction Class](../../Reconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculatePointCloudAndDepth Method
RLTitle : Reconstruction.CalculatePointCloudAndDepth Method
KeywordK : CalculatePointCloudAndDepth method
KeywordK : Reconstruction.CalculatePointCloudAndDepth method
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.CalculatePointCloudAndDepth
KeywordF : Reconstruction.CalculatePointCloudAndDepth
KeywordF : CalculatePointCloudAndDepth
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.CalculatePointCloudAndDepth(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.DepthFloatFrame)
KeywordA : M:Microsoft.Kinect.Fusion.Reconstruction.CalculatePointCloudAndDepth(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.DepthFloatFrame)
AssetID : M:Microsoft.Kinect.Fusion.Reconstruction.CalculatePointCloudAndDepth(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.DepthFloatFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Reconstruction.CalculatePointCloudAndDepth
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
