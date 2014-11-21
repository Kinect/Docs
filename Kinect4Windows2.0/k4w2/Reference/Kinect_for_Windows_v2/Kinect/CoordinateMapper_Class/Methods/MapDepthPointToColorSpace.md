CoordinateMapper.MapDepthPointToColorSpace Method  
=================================================  

Maps a point/depth from depth space to color space. <span id="syntaxSection"></span>

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
<a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a> MapDepthPointToColorSpace(  
         <a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a> depthPoint,  
         uint16 depth  
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
<td align="left"><pre><code>public <a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a> MapDepthPointToColorSpace (  
         <a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a> depthPoint,  
         UInt16 depth  
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
<td align="left"><pre><code>var colorSpacePoint = coordinateMapper.mapDepthPointToColorSpace(depthPoint, depth);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EJ"></span>
#### Parameters  

*depthPoint*    
Type: [DepthSpacePoint](../../DepthSpacePoint_Structure.md)  
 The depth value at this point.  

*depth*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

The depth value at this point.  

<span id="ID4ES"></span>
#### Return value  

Type: [ColorSpacePoint](../../ColorSpacePoint_Structure.md)  
 The mapped to camera space.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ESB"></span>

See also  
========  

<span id="ID4EUB"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapDepthPointToColorSpace Method
RLTitle : CoordinateMapper.MapDepthPointToColorSpace Method
KeywordK : MapDepthPointToColorSpace method
KeywordK : CoordinateMapper.MapDepthPointToColorSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthPointToColorSpace
KeywordF : CoordinateMapper.MapDepthPointToColorSpace
KeywordF : MapDepthPointToColorSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthPointToColorSpace(WindowsPreview.Kinect.DepthSpacePoint,System.UInt16)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthPointToColorSpace(WindowsPreview.Kinect.DepthSpacePoint,System.UInt16)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthPointToColorSpace(WindowsPreview.Kinect.DepthSpacePoint,System.UInt16)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapDepthPointToColorSpace
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
