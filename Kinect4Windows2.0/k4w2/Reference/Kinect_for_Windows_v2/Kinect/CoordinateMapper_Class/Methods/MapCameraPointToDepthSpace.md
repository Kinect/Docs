CoordinateMapper.MapCameraPointToDepthSpace Method  
==================================================  

Maps a point from camera space to depth space. <span id="syntaxSection"></span>

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
<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a> MapCameraPointToDepthSpace(  
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
<td align="left"><pre><code>public <a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a> MapCameraPointToDepthSpace (  
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
<td align="left"><pre><code>var depthSpacePoint = coordinateMapper.mapCameraPointToDepthSpace(cameraPoint);</code></pre></td>
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

Type: [DepthSpacePoint](../../DepthSpacePoint_Structure.md)  
 The point mapped to depth space.  

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
TOCTitle : MapCameraPointToDepthSpace Method
RLTitle : CoordinateMapper.MapCameraPointToDepthSpace Method
KeywordK : MapCameraPointToDepthSpace method
KeywordK : CoordinateMapper.MapCameraPointToDepthSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToDepthSpace
KeywordF : CoordinateMapper.MapCameraPointToDepthSpace
KeywordF : MapCameraPointToDepthSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToDepthSpace(WindowsPreview.Kinect.CameraSpacePoint)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToDepthSpace(WindowsPreview.Kinect.CameraSpacePoint)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToDepthSpace(WindowsPreview.Kinect.CameraSpacePoint)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointToDepthSpace
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
