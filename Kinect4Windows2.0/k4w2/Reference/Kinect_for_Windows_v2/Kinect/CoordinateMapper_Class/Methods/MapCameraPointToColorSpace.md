CoordinateMapper.MapCameraPointToColorSpace Method  
==================================================  

Maps a point from camera space to color space. <span id="syntaxSection"></span>

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
<a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a> MapCameraPointToColorSpace(  
         <a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a> cameraPoint  
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
<td align="left"><pre><code>public <a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a> MapCameraPointToColorSpace (  
         <a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a> cameraPoint  
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
<td align="left"><pre><code>var colorSpacePoint = coordinateMapper.mapCameraPointToColorSpace(cameraPoint);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EJ"></span>
#### Parameters  

*cameraPoint*    
Type: [CameraSpacePoint](../../CameraSpacePoint_Structure.md)  
 The point to map from camera space.  

<span id="ID4ES"></span>
#### Return value  

Type: [ColorSpacePoint](../../ColorSpacePoint_Structure.md)  
 The point mapped to color space.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EJB"></span>

See also  
========  

<span id="ID4ELB"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapCameraPointToColorSpace Method
RLTitle : CoordinateMapper.MapCameraPointToColorSpace Method
KeywordK : MapCameraPointToColorSpace method
KeywordK : CoordinateMapper.MapCameraPointToColorSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToColorSpace
KeywordF : CoordinateMapper.MapCameraPointToColorSpace
KeywordF : MapCameraPointToColorSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToColorSpace(WindowsPreview.Kinect.CameraSpacePoint)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToColorSpace(WindowsPreview.Kinect.CameraSpacePoint)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToColorSpace(WindowsPreview.Kinect.CameraSpacePoint)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToColorSpace
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
