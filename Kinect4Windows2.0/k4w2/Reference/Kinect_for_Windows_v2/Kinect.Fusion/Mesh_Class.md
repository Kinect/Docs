Mesh Class  
==========  

The Mesh object is created when meshing a reconstruction volume. This provides access to the vertices, vertex colors, and triangle indexes of the mesh. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class Mesh sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class Mesh</code></pre></td>
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
<td align="left"><pre><code>var mesh = Microsoft.Kinect.Fusion.Mesh;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**Mesh** has the following members.  

<span id="publicpropertiesSection"></span>

Properties  
==========  

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
<td align="left"><a href="Mesh_Class/Properties/MeshBuffer_Property.md">MeshBuffer</a></td>
<td align="left">Gets the buffer in which the mesh data is stored.</td>
</tr>
<tr class="even">
<td align="left"><a href="Mesh_Class/Properties/TriangleIndicies_Property.md">TriangleIndicies</a></td>
<td align="left">Gets the collection of triangle indexes. There are 3 indexes per triangle.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Mesh_Class/Properties/VertexColors_Property.md">VertexColors</a></td>
<td align="left">Gets the collection of vertex colors. Each color has a corresponding vertex with the same index.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EV"></span>

See also  
========  

<span id="ID4EX"></span>
#### Reference  

[Microsoft.Kinect.Fusion Namespace](../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Mesh Class
RLTitle : Mesh Class
KeywordK : Mesh class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Fusion.Mesh
KeywordF : Mesh
KeywordF : Microsoft.Kinect.Fusion.Mesh
KeywordA : T:Microsoft.Kinect.Fusion.Mesh
AssetID : T:Microsoft.Kinect.Fusion.Mesh
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Mesh
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
