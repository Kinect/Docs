CoordinateMapper.MapCameraPointsToDepthSpace Method  
===================================================  

Maps points at a specified memory location from camera space to depth space. <span id="syntaxSection"></span>

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
void MapCameraPointsToDepthSpace(  
         Array&lt;<a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a>&gt;^ cameraPoints,  
         out Array&lt;<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a>&gt;^ depthPoints  
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
<td align="left"><pre><code>public void MapCameraPointsToDepthSpace (  
         Array&lt;<a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a>&gt;[] cameraPoints,  
         out Array&lt;<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a>&gt;[] depthPoints  
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
<td align="left"><pre><code>coordinateMapper.mapCameraPointsToDepthSpace(cameraPoints, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cameraPoints*    
Type: [CameraSpacePoint](../../CameraSpacePoint_Structure.md)  
The points to map from camera space.  

*depthPoints*    
Type: [DepthSpacePoint](../../DepthSpacePoint_Structure.md)  
The array to be filled with the corresponding depth space points.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ECB"></span>

See also  
========  

<span id="ID4EEB"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapCameraPointsToDepthSpace Method
RLTitle : CoordinateMapper.MapCameraPointsToDepthSpace Method
KeywordK : MapCameraPointsToDepthSpace method
KeywordK : CoordinateMapper.MapCameraPointsToDepthSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToDepthSpace
KeywordF : CoordinateMapper.MapCameraPointsToDepthSpace
KeywordF : MapCameraPointsToDepthSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToDepthSpace(WindowsPreview.Kinect.CameraSpacePoint[],WindowsPreview.Kinect.DepthSpacePoint[]@)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToDepthSpace(WindowsPreview.Kinect.CameraSpacePoint[],WindowsPreview.Kinect.DepthSpacePoint[]@)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToDepthSpace(WindowsPreview.Kinect.CameraSpacePoint[],WindowsPreview.Kinect.DepthSpacePoint[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToDepthSpace
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
