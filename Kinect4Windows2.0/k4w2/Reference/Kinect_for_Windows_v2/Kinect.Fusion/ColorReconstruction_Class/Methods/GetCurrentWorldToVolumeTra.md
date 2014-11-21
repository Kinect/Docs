ColorReconstruction.GetCurrentWorldToVolumeTransform Method  
===========================================================  

Gets the current internal world-to-volume transform. <span id="syntaxSection"></span>

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
<a href="../../Matrix4x4_Structure.md">Matrix4x4</a> GetCurrentWorldToVolumeTransform()</code></pre></td>
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
<td align="left"><pre><code>public <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> GetCurrentWorldToVolumeTransform ()</code></pre></td>
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
<td align="left"><pre><code>var matrix4x4 = colorReconstruction.getCurrentWorldToVolumeTransform();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 Returns the current world-to-volume transform. This is a similarity transformation that converts world coordinates to volume coordinates.  

<span id="remarks"></span>

Remarks  
=======  

A right handed coordinate system is used, with the origin of the volume (that is, voxel 0,0,0) at the top left of the front plane of the cube. Similar to bitmap images with top left origin, +X is to the right, +Y down, and +Z is forward from the origin into the reconstruction volume..  

The default transformation is a combination of translation in x-axis and y-axis to locate the world origin at the center of the front face of the reconstruction volume cube, and scaling by the [ReconstructionParameters.VoxelsPerMeter](../../ReconstructionParameters/ReconstructionParameters/VoxelsPerMeter_Field.md) field to convert from the world coordinate system to volume voxel indices.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4ENB"></span>

See also  
========  

<span id="ID4EPB"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetCurrentWorldToVolumeTransform Method
RLTitle : ColorReconstruction.GetCurrentWorldToVolumeTransform Method
KeywordK : GetCurrentWorldToVolumeTransform method
KeywordK : ColorReconstruction.GetCurrentWorldToVolumeTransform method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.GetCurrentWorldToVolumeTransform
KeywordF : ColorReconstruction.GetCurrentWorldToVolumeTransform
KeywordF : GetCurrentWorldToVolumeTransform
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.GetCurrentWorldToVolumeTransform
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.GetCurrentWorldToVolumeTransform
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.GetCurrentWorldToVolumeTransform
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.GetCurrentWorldToVolumeTransform
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
