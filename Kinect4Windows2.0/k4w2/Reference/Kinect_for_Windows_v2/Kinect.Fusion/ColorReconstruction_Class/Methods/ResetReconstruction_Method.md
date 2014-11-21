ColorReconstruction.ResetReconstruction Method  
==============================================  

Clears the reconstruction volume and sets a new world-to-camera transform (camera view pose). <span id="syntaxSection"></span>

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
void ResetReconstruction(  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> initialWorldToCameraTransform,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToVolumeTransform  
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
<td align="left"><pre><code>public void ResetReconstruction (  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> initialWorldToCameraTransform,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToVolumeTransform  
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
<td align="left"><pre><code>colorReconstruction.resetReconstruction(initialWorldToCameraTransform, worldToVolumeTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*initialWorldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The initial camera pose of the reconstruction volume, with respect to the world origin. To use the default camera pose, specify identity.  

*worldToVolumeTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The world-to-volume transform that expresses the location and orientation of the world coordinate system origin in volume coordinates, as well as the scaling of the world coordinates to volume indices. This controls where the reconstruction volume appears in the real world with respect to the world origin position, or with respect to the camera if identity is passed to the *initialWorldToCameraTransform* parameter (as this causes the camera and world origins to coincide).  

<span id="remarks"></span>

Remarks  
=======  

To create your own world-to-volume transformation, call the [GetCurrentWorldToVolumeTransform](GetCurrentWorldToVolumeTra.md) method, and then either modify the returned matrix directly or multiply with your own similarity matrix to alter the volume translation or rotation with respect to the world coordinate system. Other transforms, such as skew, are not supported.  

To reset the volume while keeping the same world-to-volume transform, call the **GetCurrentWorldToVolumeTransform** method, and then pass the returned matrix to the *worldToVolumeTransform* parameter of the **ResetReconstruction** method.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E1B"></span>

See also  
========  

<span id="ID4E3B"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ResetReconstruction Method
RLTitle : ColorReconstruction.ResetReconstruction Method
KeywordK : ResetReconstruction method
KeywordK : ColorReconstruction.ResetReconstruction method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.ResetReconstruction
KeywordF : ColorReconstruction.ResetReconstruction
KeywordF : ResetReconstruction
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.ResetReconstruction(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.ResetReconstruction(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.ResetReconstruction(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.ResetReconstruction
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
