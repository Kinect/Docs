CoordinateMapper.GetDepthFrameToCameraSpaceTable Method  
=======================================================  

Gets the depth frame to camera space look-up table. <span id="syntaxSection"></span>

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
Point^ GetDepthFrameToCameraSpaceTable()</code></pre></td>
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
<td align="left"><pre><code>public Point[] GetDepthFrameToCameraSpaceTable ()</code></pre></td>
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
<td align="left"><pre><code>var point = coordinateMapper.getDepthFrameToCameraSpaceTable();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The look-up table.  

<span id="remarks"></span>

Remarks  
=======  

Each entry in the returned look-up table maps the corresponding depth frame pixel to a point in camera space. To find the X and Y coordinates of a depth point in camera space, multiply the depth pixel value by the coordinates in the corresponding entry in the look-up table. Note that depth pixel values are in millimeters.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetDepthFrameToCameraSpaceTable Method
RLTitle : CoordinateMapper.GetDepthFrameToCameraSpaceTable Method
KeywordK : GetDepthFrameToCameraSpaceTable method
KeywordK : CoordinateMapper.GetDepthFrameToCameraSpaceTable method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.GetDepthFrameToCameraSpaceTable
KeywordF : CoordinateMapper.GetDepthFrameToCameraSpaceTable
KeywordF : GetDepthFrameToCameraSpaceTable
KeywordF : WindowsPreview.Kinect.CoordinateMapper.GetDepthFrameToCameraSpaceTable
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.GetDepthFrameToCameraSpaceTable
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.GetDepthFrameToCameraSpaceTable
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.GetDepthFrameToCameraSpaceTable
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
