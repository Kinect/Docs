Reconstruction.ResetReconstruction Method  
=========================================  

Clear the reconstruction volume, and set a world-to-camera transform (camera view pose) and a world-to-volume transform.  
The world-volume transform expresses the location and orientation of the world coordinate system origin in volume coordinates and the scaling of the world coordinates to volume indices. In practice, this controls where the reconstruction volume appears in the real world with respect to the world origin position, or with respect to the camera if identity is passed for the initial world-to-camera transform (as the camera and world origins then coincide).  

To create your own world-volume transformation first get the current transform by calling GetCurrentWorldToVolumeTransform then either modify the matrix directly or multiply with your own similarity matrix to alter the volume translation or rotation with respect to the world coordinate system. Note that other transforms such as skew are not supported. To reset the volume while keeping the same world-volume transform, first get the current transform by calling GetCurrentWorldToVolumeTransform and pass this Matrix4 as the *worldToVolumeTransform* parameter when calling this reset function.  

<span id="syntaxSection"></span>

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
<td align="left"><pre><code>reconstruction.resetReconstruction(initialWorldToCameraTransform, worldToVolumeTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EN"></span>
#### Parameters  

*initialWorldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The initial camera pose with respect to the world origin. Pass identity as the default camera pose.  

*worldToVolumeTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 A Matrix4 instance, containing the world to volume transform.  

This method raises the following exceptions:  

|---------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Exception**             | **Raised By**                                                                                                                |
| InvalidOperationException | Thrown when the Kinect Runtime could not be accessed, the device is not connected, or the call failed for an unknown reason. |

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
TOCTitle : ResetReconstruction Method
RLTitle : Reconstruction.ResetReconstruction Method
KeywordK : ResetReconstruction method
KeywordK : Reconstruction.ResetReconstruction method
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.ResetReconstruction
KeywordF : Reconstruction.ResetReconstruction
KeywordF : ResetReconstruction
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.ResetReconstruction(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.Reconstruction.ResetReconstruction(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.Reconstruction.ResetReconstruction(Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Reconstruction.ResetReconstruction
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
