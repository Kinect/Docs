PointCloudFrame Class  
=====================  

A frame used specifically for float-based point cloud images. It provides access to the dimensions, format and pixel data for a depth frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class PointCloudFrame sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class PointCloudFrame</code></pre></td>
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
<td align="left"><pre><code>var pointCloudFrame = Microsoft.Kinect.Fusion.PointCloudFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**PointCloudFrame** has the following members.  

<span id="publicconstructorsSection"></span>

Constructors  
============  

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
<td align="left"><a href="PointCloudFrame_Class/Constructor.md">PointCloudFrame</a></td>
<td align="left">Initializes a new instance of the <a href="">PointCloudFrame</a> class.</td>
</tr>
</tbody>
</table>

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
<td align="left"><a href="PointCloudFrame_Class/Properties/CameraParameters_Property.md">CameraParameters</a></td>
<td align="left">Gets the camera parameters associated with the frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="PointCloudFrame_Class/Properties/FrameBuffer_Property.md">FrameBuffer</a></td>
<td align="left">Gets the buffer where the image data for the frame is stored.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PointCloudFrame_Class/Properties/Height_Property.md">Height</a></td>
<td align="left">Gets the height of the frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="PointCloudFrame_Class/Properties/Width_Property.md">Width</a></td>
<td align="left">Gets the width of the frame.</td>
</tr>
</tbody>
</table>

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
<td align="left"><a href="PointCloudFrame_Class/Methods/Shade_Method.md">Shade</a></td>
<td align="left">Produces a shaded image from the point cloud frame, based only on point position.</td>
</tr>
<tr class="even">
<td align="left"><a href="PointCloudFrame_Class/Methods/ShadeWithNormals_Method.md">ShadeWithNormals</a></td>
<td align="left">Overloaded. Produces one or two shaded images from the point cloud frame, based on point position and surface normal.</td>
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
TOCTitle : PointCloudFrame Class
RLTitle : PointCloudFrame Class
KeywordK : PointCloudFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Fusion.PointCloudFrame
KeywordF : PointCloudFrame
KeywordF : Microsoft.Kinect.Fusion.PointCloudFrame
KeywordA : T:Microsoft.Kinect.Fusion.PointCloudFrame
AssetID : T:Microsoft.Kinect.Fusion.PointCloudFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.PointCloudFrame
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
