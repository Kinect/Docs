INuiFusionMesh Interface  
========================  

The Mesh object is created when meshing a reconstruction volume. This provides access to the vertices, normals, and triangle indexes of the mesh. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface INuiFusionMesh : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionMesh** has the following members.  

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
<td align="left"><a href="INuiFusionMesh_Interface/Methods/GetNormals_Method.md">GetNormals</a></td>
<td align="left">Gets the mesh normals.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMesh_Interface/Methods/GetTriangleIndices_Method.md">GetTriangleIndices</a></td>
<td align="left">Gets the mesh triangle indices.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionMesh_Interface/Methods/GetVertices_Method.md">GetVertices</a></td>
<td align="left">Gets the mesh vertices.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMesh_Interface/Methods/NormalCount_Method.md">NormalCount</a></td>
<td align="left">Gets the number of normals in the mesh.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionMesh_Interface/Methods/TriangleVertexIndexCount.md">TriangleVertexIndexCount</a></td>
<td align="left">Gets the number of triangle vertex indices for the mesh.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMesh_Interface/Methods/VertexCount_Method.md">VertexCount</a></td>
<td align="left">Gets the number of vertices in the mesh.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionMesh Interface
RLTitle : INuiFusionMesh Interface
KeywordK : INuiFusionMesh interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionMesh
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh
KeywordA : T:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh
AssetID : T:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
