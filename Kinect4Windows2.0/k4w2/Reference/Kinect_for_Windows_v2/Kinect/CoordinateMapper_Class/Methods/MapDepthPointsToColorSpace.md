CoordinateMapper.MapDepthPointsToColorSpace Method  
==================================================  

Produces an array of color space points from an array of depth points. <span id="syntaxSection"></span>

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
void MapDepthPointsToColorSpace(  
         Array&lt;<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a>&gt;^ depthPoints,  
         Array&lt;uint16&gt;^ depths,  
         out Array&lt;<a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a>&gt;^ colorPoints  
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
<td align="left"><pre><code>public void MapDepthPointsToColorSpace (  
         Array&lt;<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a>&gt;[] depthPoints,  
         Array&lt;UInt16&gt;[] depths,  
         out Array&lt;<a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a>&gt;[] colorPoints  
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
<td align="left"><pre><code>coordinateMapper.mapDepthPointsToColorSpace(depthPoints, depths, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthPoints*    
Type: [DepthSpacePoint](../../DepthSpacePoint_Structure.md)  
The points in depth space.  

*depths*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

The depths of each point in depth space.  

*colorPoints*    
Type: [ColorSpacePoint](../../ColorSpacePoint_Structure.md)  
A reference to an array to be filled with the calculated color space points.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapDepthPointsToColorSpace Method
RLTitle : CoordinateMapper.MapDepthPointsToColorSpace Method
KeywordK : MapDepthPointsToColorSpace method
KeywordK : CoordinateMapper.MapDepthPointsToColorSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthPointsToColorSpace
KeywordF : CoordinateMapper.MapDepthPointsToColorSpace
KeywordF : MapDepthPointsToColorSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthPointsToColorSpace(WindowsPreview.Kinect.DepthSpacePoint[],System.UInt16[],WindowsPreview.Kinect.ColorSpacePoint[]@)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthPointsToColorSpace(WindowsPreview.Kinect.DepthSpacePoint[],System.UInt16[],WindowsPreview.Kinect.ColorSpacePoint[]@)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthPointsToColorSpace(WindowsPreview.Kinect.DepthSpacePoint[],System.UInt16[],WindowsPreview.Kinect.ColorSpacePoint[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapDepthPointsToColorSpace
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
