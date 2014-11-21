PointCloudFrame.ShadeWithNormals Method (Matrix4x4, Matrix4x4, ColorImageFrame, ColorImageFrame)  
================================================================================================  

Produces one or two shaded images from the point cloud frame, based on point position and surface normal. <span id="syntaxSection"></span>

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
void ShadeWithNormals(  
         <a href="../../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform,  
         <a href="../../../Matrix4x4_Structure.md">Matrix4x4</a> worldToRGBTransform,  
         <a href="../../../ColorImageFrame_Class.md">ColorImageFrame</a>^ shadedSurfaceNormalsFrame,  
         <a href="../../../ColorImageFrame_Class.md">ColorImageFrame</a>^ shadedSurfaceFrame  
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
<td align="left"><pre><code>public void ShadeWithNormals (  
         <a href="../../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform,  
         <a href="../../../Matrix4x4_Structure.md">Matrix4x4</a> worldToRGBTransform,  
         <a href="../../../ColorImageFrame_Class.md">ColorImageFrame</a>shadedSurfaceNormalsFrame,  
         <a href="../../../ColorImageFrame_Class.md">ColorImageFrame</a>shadedSurfaceFrame  
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
<td align="left"><pre><code>pointCloudFrame.shadeWithNormals(worldToCameraTransform, worldToRGBTransform, shadedSurfaceNormalsFrame, shadedSurfaceFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*worldToCameraTransform*    
Type: [Matrix4x4](../../../Matrix4x4_Structure.md)  
 The transform used to determine the perspective of the shaded point cloud relative to the world. This affects the application of the worldToRGBTramsform to the point cloud. To achieve consistent results, this should match the world-to-camera transform that was used to create the [PointCloudFrame](../../../PointCloudFrame_Class.md)  

*worldToRGBTransform*    
Type: [Matrix4x4](../../../Matrix4x4_Structure.md)  
 The transform that defines a mapping from position to RGB color space. The X, Y, Z components of the point positions transformed by this matrix are used as the R, G, B values in the rendered frame.  

*shadedSurfaceNormalsFrame*    
Type: [ColorImageFrame](../../../ColorImageFrame_Class.md)  
A color image frame that receives the shaded frame which includes lighting based on the surface normal.  

*shadedSurfaceFrame*    
Type: [ColorImageFrame](../../../ColorImageFrame_Class.md)  
A color image frame that receives the shaded frame.  

<span id="remarks"></span>

Remarks  
=======  

This method is provided to enable interactive display of point cloud data.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EVB"></span>

See also  
========  

<span id="ID4EXB"></span>
#### Reference  

[PointCloudFrame Class](../../../PointCloudFrame_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ShadeWithNormals Method (Matrix4x4, Matrix4x4, ColorImageFrame, ColorImageFrame)
RLTitle : PointCloudFrame.ShadeWithNormals Method (Matrix4x4, Matrix4x4, ColorImageFrame, ColorImageFrame)
KeywordA : M:Microsoft.Kinect.Fusion.PointCloudFrame.ShadeWithNormals(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.ColorImageFrame)
AssetID : M:Microsoft.Kinect.Fusion.PointCloudFrame.ShadeWithNormals(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.ColorImageFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.PointCloudFrame.ShadeWithNormals
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
