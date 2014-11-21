INuiFusionColorMesh Interface  
=============================  

The INuiFusionColorMesh object is created when meshing a reconstruction volume. This provides access to the vertices, vertex colors, and triangle indexes of the mesh. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface INuiFusionColorMesh : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionColorMesh** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="INuiFusionColorMesh/Methods/ColorCount_Method.md">ColorCount</a></td>
<td align="left">Gets the number of colors in the mesh.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionColorMesh/Methods/GetColors_Method.md">GetColors</a></td>
<td align="left">Gets the collection of vertex colors.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionColorMesh/Methods/GetNormals_Method.md">GetNormals</a></td>
<td align="left">Gets the list of normals for the mesh.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionColorMesh/Methods/GetTriangleIndices_Method.md">GetTriangleIndices</a></td>
<td align="left">Gets the list of triangle indices for the mesh.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionColorMesh/Methods/GetVertices_Method.md">GetVertices</a></td>
<td align="left">Gets the list of vertices for the mesh.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionColorMesh/Methods/NormalCount_Method.md">NormalCount</a></td>
<td align="left">Gets the number of normals in the mesh.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionColorMesh/Methods/TriangleVertexIndexCount.md">TriangleVertexIndexCount</a></td>
<td align="left">Gets the number of triangle vertex indices in the mesh.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionColorMesh/Methods/VertexCount_Method.md">VertexCount</a></td>
<td align="left">Gets the number of vertices in the mesh.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionColorMesh Interface
RLTitle : INuiFusionColorMesh Interface
KeywordK : INuiFusionColorMesh interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionColorMesh
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh
KeywordA : T:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh
AssetID : T:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
