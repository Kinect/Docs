ColorReconstruction.AlignPointClouds Method  
===========================================  

Aligns two sets of overlapping oriented point clouds and calculates the camera's relative pose. <span id="syntaxSection"></span>

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
<a href="../../AlignmentResult_Class.md">AlignmentResult</a>^ AlignPointClouds(  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>^ referenceFrame,  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>^ observedFrame,  
         uint16 maxAlignIterationCount,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> referenceToObservedTransform,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>^ deltaFromReferenceFrame  
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
<td align="left"><pre><code>public <a href="../../AlignmentResult_Class.md">AlignmentResult</a>AlignPointClouds (  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>referenceFrame,  
         <a href="../../PointCloudFrame_Class.md">PointCloudFrame</a>observedFrame,  
         UInt16 maxAlignIterationCount,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> referenceToObservedTransform,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>deltaFromReferenceFrame  
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
<td align="left"><pre><code>var alignmentResult = colorReconstruction.alignPointClouds(referenceFrame, observedFrame, maxAlignIterationCount, referenceToObservedTransform, deltaFromReferenceFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*referenceFrame*    
Type: [PointCloudFrame](../../PointCloudFrame_Class.md)  
 A reference point cloud frame. This image must be the same size and have the same camera parameters as the *observedPointCloudFrame* parameter.  

*observedFrame*    
Type: [PointCloudFrame](../../PointCloudFrame_Class.md)  
 An observed point cloud frame. This image must be the same size and have the same camera parameters as the *referencePointCloudFrame* parameter.  

*maxAlignIterationCount*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

The number of iterations to run.  

*referenceToObservedTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 A matrix that receives the initial guess at the transform. This is updated when tracking succeeds. Tracking failure is indicated by a value of identity.  

*deltaFromReferenceFrame*    
Type: [ColorImageFrame](../../ColorImageFrame_Class.md)  

Optional pre-allocated color image frame that receives color-coded data from the camera tracking. This image can be used as input to additional vision algorithms, such as object segmentation. If specified, this image must be the same size and have the same camera parameters as the *referencePointCloudFrame* and *observedPointCloudFrame* parameters. If you do not need this output image, specify **null**.  

The values in the received image vary depending on whether the pixel was a valid pixel used in tracking (inlier) or failed in different tests (outlier). Inliers are color shaded depending on the residual energy at that point. Higher discrepancy between vertices is indicated by more saturated colors. Less discrepancy between vertices (less information at that pixel) is indicated by less saturated colors (that is, more white). If the pixel is an outlier, it will receive one of the values listed in the following table.  

| Value      | Description                                                                                                                                                |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0xFF000000 | The input vertex was invalid (for example, a vertex with an input depth of zero), or the vertex had no correspondences between the two point cloud images. |
| 0xFF008000 | The outlier vertices were rejected due to too large a distance between vertices.                                                                           |
| 0xFF800000 | The outlier vertices were rejected due to too large a difference in normal angle between the point clouds.                                                 |

<span id="ID4EP"></span>
#### Return value  

Type: [AlignmentResult](../../AlignmentResult_Class.md)  
The result of the alignment operation.  

<span id="remarks"></span>

Remarks  
=======  

This method runs on the GPU as an iterative algorithm.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EOD"></span>

See also  
========  

<span id="ID4EQD"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AlignPointClouds Method
RLTitle : ColorReconstruction.AlignPointClouds Method
KeywordK : AlignPointClouds method
KeywordK : ColorReconstruction.AlignPointClouds method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.AlignPointClouds
KeywordF : ColorReconstruction.AlignPointClouds
KeywordF : AlignPointClouds
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.AlignPointClouds(Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.PointCloudFrame,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.ColorImageFrame)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.AlignPointClouds(Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.PointCloudFrame,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.ColorImageFrame)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.AlignPointClouds(Microsoft.Kinect.Fusion.PointCloudFrame,Microsoft.Kinect.Fusion.PointCloudFrame,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.ColorImageFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.AlignPointClouds
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
