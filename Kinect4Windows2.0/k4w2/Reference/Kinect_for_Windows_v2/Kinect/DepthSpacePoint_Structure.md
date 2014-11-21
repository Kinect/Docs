DepthSpacePoint Structure  
=========================  

Represents pixel coordinates within a depth image. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public value struct DepthSpacePoint</code></pre></td>
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
<td align="left"><pre><code>public struct DepthSpacePoint</code></pre></td>
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
<td align="left"><pre><code>var depthSpacePoint = {  
      x : /* Your value */,   
      y : /* Your value */  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**DepthSpacePoint** has the following members.  

<span id="publicfieldsSection"></span>

Fields  
======  

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
<td align="left"><a href="DepthSpacePoint_Structure/DepthSpacePoint_Fields/X_Field.md">X</a></td>
<td align="left">The X coordinate of the point, in pixels.</td>
</tr>
<tr class="even">
<td align="left"><a href="DepthSpacePoint_Structure/DepthSpacePoint_Fields/Y_Field.md">Y</a></td>
<td align="left">The Y coordinate of the point, in pixels.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

Depth space is the term used to describe a 2D location on the depth image. Think of this as a row/column location of a pixel where x is the column and y is the row. So x=0, y=0 corresponds to the top left corner of the image and x=511, y=423 (width-1, height-1) is the bottom right corner of the image. In some cases, a z value is needed in order to map out of depth space. For these cases, simply sample the depth image at the row/column in question, and use that value (which is depth in millimeters) directly as z.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DepthSpacePoint Structure
RLTitle : DepthSpacePoint Structure
KeywordK : DepthSpacePoint structure, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.DepthSpacePoint
KeywordF : DepthSpacePoint
KeywordF : WindowsPreview.Kinect.DepthSpacePoint
KeywordA : T:WindowsPreview.Kinect.DepthSpacePoint
AssetID : T:WindowsPreview.Kinect.DepthSpacePoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.DepthSpacePoint
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
