ColorReconstruction.IntegrateFrame Method  
=========================================  

Integrates depth float data and color data into the reconstruction volume from the specified camera pose. <span id="syntaxSection"></span>

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
void IntegrateFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>^ colorImageFrame,  
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
<td align="left"><pre><code>public void IntegrateFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>colorImageFrame,  
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
<td align="left"><pre><code>colorReconstruction.integrateFrame(depthFloatFrame, colorImageFrame, maxIntegrationWeight, maxColorIntegrationAngle, worldToCameraTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
The depth float frame to be integrated.  

*colorImageFrame*    
Type: [ColorImageFrame](../../ColorImageFrame_Class.md)  
The color frame to be integrated.  

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

The camera pose. This is usually the camera pose result from the most recent call to the [ColorReconstruction.AlignPointClouds](AlignPointClouds_Method.md) or [ColorReconstruction.AlignDepthFloatFrameToReconstruction](AlignDepthFloatFrameToReco.md) method.  

| ![](../../../../../../resources/note.gif)Note                |
|--------------------------------------------------------------|
| This method also sets the internal camera pose to this pose. |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4ENC"></span>

See also  
========  

<span id="ID4EPC"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IntegrateFrame Method
RLTitle : ColorReconstruction.IntegrateFrame Method
KeywordK : IntegrateFrame method
KeywordK : ColorReconstruction.IntegrateFrame method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.IntegrateFrame
KeywordF : ColorReconstruction.IntegrateFrame
KeywordF : IntegrateFrame
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.IntegrateFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,System.UInt16,System.Single,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.IntegrateFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,System.UInt16,System.Single,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.IntegrateFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,System.UInt16,System.Single,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.IntegrateFrame
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
