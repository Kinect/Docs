ColorReconstruction.CalculateMesh Method  
========================================  

Exports a polygon mesh of the zero-crossing dense surfaces from the reconstruction volume with per-vertex color. <span id="syntaxSection"></span>

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
<a href="../../Mesh_Class.md">Mesh</a>^ CalculateMesh(  
         int32 voxelStep  
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
<td align="left"><pre><code>public <a href="../../Mesh_Class.md">Mesh</a>CalculateMesh (  
         int voxelStep  
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
<td align="left"><pre><code>var mesh = colorReconstruction.calculateMesh(voxelStep);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*voxelStep*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The step value in voxels for sampling points to use in the volume when exporting a mesh, which determines the final resolution of the mesh. Use higher values for lower resolution meshes. This value must be greater than zero and smaller than the smallest volume axis voxel resolution. To mesh the volume at its full resolution, use a step value of one.  

| ![](../../../../../../resources/note.gif)Note                                                                                        |
|--------------------------------------------------------------------------------------------------------------------------------------|
| Any value higher than one for this parameter runs the risk of missing zero crossings, and hence missing surfaces or surface details. |

<span id="ID4EP"></span>
#### Return value  

Type: [Mesh](../../Mesh_Class.md)  
 Returns the created [Mesh](../../Mesh_Class.md) object.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculateMesh Method
RLTitle : ColorReconstruction.CalculateMesh Method
KeywordK : CalculateMesh method
KeywordK : ColorReconstruction.CalculateMesh method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.CalculateMesh
KeywordF : ColorReconstruction.CalculateMesh
KeywordF : CalculateMesh
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.CalculateMesh(System.Int32)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.CalculateMesh(System.Int32)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.CalculateMesh(System.Int32)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.CalculateMesh
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
