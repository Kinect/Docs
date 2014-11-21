CoordinateMapper.MapCameraPointsToColorSpace Method  
===================================================  

Produces an array of color space points from an array of camera points. <span id="syntaxSection"></span>

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
void MapCameraPointsToColorSpace(  
         Array&lt;<a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a>&gt;^ cameraPoints,  
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
<td align="left"><pre><code>public void MapCameraPointsToColorSpace (  
         Array&lt;<a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a>&gt;[] cameraPoints,  
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
<td align="left"><pre><code>coordinateMapper.mapCameraPointsToColorSpace(cameraPoints, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cameraPoints*    
Type: [CameraSpacePoint](../../CameraSpacePoint_Structure.md)  
The points in camera space  

*colorPoints*    
Type: [ColorSpacePoint](../../ColorSpacePoint_Structure.md)  
Reference to an array to be filled with the corresponding color space points.  

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
TOCTitle : MapCameraPointsToColorSpace Method
RLTitle : CoordinateMapper.MapCameraPointsToColorSpace Method
KeywordK : MapCameraPointsToColorSpace method
KeywordK : CoordinateMapper.MapCameraPointsToColorSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToColorSpace
KeywordF : CoordinateMapper.MapCameraPointsToColorSpace
KeywordF : MapCameraPointsToColorSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToColorSpace(WindowsPreview.Kinect.CameraSpacePoint[],WindowsPreview.Kinect.ColorSpacePoint[]@)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToColorSpace(WindowsPreview.Kinect.CameraSpacePoint[],WindowsPreview.Kinect.ColorSpacePoint[]@)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToColorSpace(WindowsPreview.Kinect.CameraSpacePoint[],WindowsPreview.Kinect.ColorSpacePoint[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapCameraPointsToColorSpace
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
