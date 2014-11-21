ColorReconstruction.ProcessFrame Method  
=======================================  

Processes the specified depth frame and color frame through the Kinect Fusion pipeline. <span id="syntaxSection"></span>

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
<a href="../../AlignmentResult_Class.md">AlignmentResult</a>^ ProcessFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>^ colorImageFrame,  
         uint16 maxAlignIterationCount,  
         uint16 maxIntegrationWeight,  
         float32 maxColorIntegrationAngle,  
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
<td align="left"><pre><code>public <a href="../../AlignmentResult_Class.md">AlignmentResult</a>ProcessFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>colorImageFrame,  
         UInt16 maxAlignIterationCount,  
         UInt16 maxIntegrationWeight,  
         float maxColorIntegrationAngle,  
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
<td align="left"><pre><code>var alignmentResult = colorReconstruction.processFrame(depthFloatFrame, colorImageFrame, maxAlignIterationCount, maxIntegrationWeight, maxColorIntegrationAngle, worldToCameraTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
 The depth float frame to be processed. The maximum resolution of this frame is 640×480.  

*colorImageFrame*    
Type: [ColorImageFrame](../../ColorImageFrame_Class.md)  
 The color frame to be processed. The maximum resolution of this frame is 640×480.  

*maxAlignIterationCount*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

The maximum number of iterations of the algorithm to run. The minimum value is one. Using only a small number of iterations will have a faster run time, but the algorithm may not converge to the correct transformation.  

*maxIntegrationWeight*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

A parameter to control the temporal smoothing of depth integration. The minimum value is one. Lower values have more noisy representations, but are suitable for more dynamic environments because moving objects integrate and disintegrate faster. Higher values integrate objects more slowly, but provide finer detail with less noise.  

*maxColorIntegrationAngle*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

Angle with respect to the surface normal over which color will be integrated, in degrees. The useful range of values for this parameter is [0.0f, 90.0f]. You can use this parameter to integrate color only when the Kinect sensor is nearly parallel with the surface (that is, the camera direction of view is perpendicular to the surface), or within a specified angle from the surface normal direction.  

This angle relative to this normal direction vector describes the acceptance half angle; for example, a +/- 90 degree acceptance angle in all directions (that is, a 180 degree hemisphere) relative to the normal integrates color in any orientation of the sensor towards the front of the surface, even when parallel to the surface. An acceptance angle of zero integrates color only directly along a single ray exactly perpendicular to the surface.  

Setting this value has a cost at run-time. However, not setting this value causes this method to integrate color from any angle over all voxels along camera rays around the zero crossing surface region in the volume, which can cause thin structures to have the same color on both sides.  

*worldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The best guess at the current camera pose. This is usually the camera pose result from the most recent call to the [ColorReconstruction.AlignPointClouds](AlignPointClouds_Method.md) or [ColorReconstruction.AlignDepthFloatFrameToReconstruction](AlignDepthFloatFrameToReco.md) method.  

<span id="ID4ET"></span>
#### Return value  

Type: [AlignmentResult](../../AlignmentResult_Class.md)  
The result of the operation.  

<span id="remarks"></span>

Remarks  
=======  

This method is equivalent to calling the [AlignDepthFloatFrameToReconstruction](AlignDepthFloatFrameToReco.md) and [IntegrateFrame](IntegrateFrame_Method.md) methods on the specified depth frame. You can call these low-level methods individually to have more control over the operation, but calling **ProcessFrame** will complete faster due to the integrated nature of the calls.  

| ![](../../../../../../resources/note.gif)Note                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| If a tracking error occurs during the **AlignDepthFloatToReconstruction** call, no depth data integration will be performed and the camera pose will remain unchanged. |

If you need a visible output image of the reconstruction, call the [CalculatePointCloud](CalculatePointCloud_Method.md) method and then call the [PointCloudFrame.Shade](../../PointCloudFrame_Class/Methods/Shade_Method.md) method.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E5D"></span>

See also  
========  

<span id="ID4EAE"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : ColorReconstruction.ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : ColorReconstruction.ProcessFrame method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.ProcessFrame
KeywordF : ColorReconstruction.ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,System.UInt16,System.UInt16,System.Single,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,System.UInt16,System.UInt16,System.Single,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,System.UInt16,System.UInt16,System.Single,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.ProcessFrame
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
