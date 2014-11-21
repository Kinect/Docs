ColorReconstruction.CalculatePointCloud Method  
==============================================  

Calculates a point cloud by raycasting into the reconstruction volume, returning the point cloud containing 3D points and normals of the zero-crossing dense surface at every visible pixel in the image from the specified camera pose and color visualization image. <span id="syntaxSection"></span>

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
void CalculatePointCloud(  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>^ pointCloudFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>^ colorImageFrame,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform  
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
<td align="left"><pre><code>public void CalculatePointCloud (  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>pointCloudFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>colorImageFrame,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform  
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
<td align="left"><pre><code>colorReconstruction.calculatePointCloud(pointCloudFrame, colorImageFrame, worldToCameraTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pointCloudFrame*    
Type: [PointCloudFrame](../../PointCloudFrame_Class.md)  

The pre-allocated point cloud frame, to be filled by raycasting into the reconstruction volume. This point cloud can be used as a reference frame in the next call to the [ColorReconstruction.AlignPointClouds](AlignPointClouds_Method.md) method, or passed to the [PointCloudFrame.Shade](../../PointCloudFrame_Class/Methods/Shade_Method.md) method to produce a visible image output.  

The cloud frame can be an arbitrary image size. This allows you to calculate point clouds at the size of your window and then create a visible image by calling the **FusionDepthProcessor.ShadePointCloud** method to render this image. Note that large images are expensive to calculate.  

*colorImageFrame*    
Type: [ColorImageFrame](../../ColorImageFrame_Class.md)  
The color frame to fill.  

*worldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
The world-to-camera transform (camera pose) to raycast from.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E2B"></span>

See also  
========  

<span id="ID4E4B"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculatePointCloud Method
RLTitle : ColorReconstruction.CalculatePointCloud Method
KeywordK : CalculatePointCloud method
KeywordK : ColorReconstruction.CalculatePointCloud method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.CalculatePointCloud
KeywordF : ColorReconstruction.CalculatePointCloud
KeywordF : CalculatePointCloud
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.CalculatePointCloud(Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.CalculatePointCloud(Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.CalculatePointCloud(Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.CalculatePointCloud
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
