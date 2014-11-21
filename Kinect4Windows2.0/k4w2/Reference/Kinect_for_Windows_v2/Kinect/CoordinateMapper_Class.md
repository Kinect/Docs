CoordinateMapper Class  
======================  

Represents the mapper that provides translation services from one type of point to another. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class CoordinateMapper sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class CoordinateMapper</code></pre></td>
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
<td align="left"><pre><code>var coordinateMapper = WindowsPreview.Kinect.CoordinateMapper;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**CoordinateMapper** has the following members.  

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
<td align="left"><a href="CoordinateMapper_Class/Methods/GetDepthCameraIntrinsics.md">GetDepthCameraIntrinsics</a></td>
<td align="left">Returns the calibration data for the depth camera.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/GetDepthFrameToCameraSpace.md">GetDepthFrameToCameraSpaceTable</a></td>
<td align="left">Gets the depth frame to camera space look-up table.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapCameraPointsToColorSpace.md">MapCameraPointsToColorSpace</a></td>
<td align="left">Produces an array of color space points from an array of camera points.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapCameraPointsToDepthSpace.md">MapCameraPointsToDepthSpace</a></td>
<td align="left">Maps points at a specified memory location from camera space to depth space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapCameraPointToColorSpace.md">MapCameraPointToColorSpace</a></td>
<td align="left">Maps a point from camera space to color space.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapCameraPointToDepthSpace.md">MapCameraPointToDepthSpace</a></td>
<td align="left">Maps a point from camera space to depth space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapColorFrameToCameraSpace.md">MapColorFrameToCameraSpace</a></td>
<td align="left">Maps a frame from color space to camera space.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapColorFrameToCameraSpace.md">MapColorFrameToCameraSpaceUsingIBuffer</a></td>
<td align="left">Maps a frame from color space to camera space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapColorFrameToDepthSpace.md">MapColorFrameToDepthSpace</a></td>
<td align="left">Maps a frame from color space to depth space.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapColorFrameToDepthSpaceU.md">MapColorFrameToDepthSpaceUsingIBuffer</a></td>
<td align="left">Maps a frame from color space to depth space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthFrameToCameraSpace.md">MapDepthFrameToCameraSpace</a></td>
<td align="left">Maps a frame from depth space to camera space.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthFrameToCameraSpace.md">MapDepthFrameToCameraSpaceUsingIBuffer</a></td>
<td align="left">Maps a frame from depth space to camera space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthFrameToColorSpace.md">MapDepthFrameToColorSpace</a></td>
<td align="left">Maps a frame from depth space to color space.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthFrameToColorSpaceU.md">MapDepthFrameToColorSpaceUsingIBuffer</a></td>
<td align="left">Maps a frame from depth space to color space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthPointsToCameraSpace.md">MapDepthPointsToCameraSpace</a></td>
<td align="left">Produces an array of camera space points from an array of depth points.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthPointsToColorSpace.md">MapDepthPointsToColorSpace</a></td>
<td align="left">Produces an array of color space points from an array of depth points.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthPointToCameraSpace.md">MapDepthPointToCameraSpace</a></td>
<td align="left">Maps a point/depth from depth space to camera space.</td>
</tr>
<tr class="even">
<td align="left"><a href="CoordinateMapper_Class/Methods/MapDepthPointToColorSpace.md">MapDepthPointToColorSpace</a></td>
<td align="left">Maps a point/depth from depth space to color space.</td>
</tr>
</tbody>
</table>

<span id="publiceventsSection"></span>

Events  
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
<td align="left"><a href="CoordinateMapper_Class/Events/CoordinateMappingChanged.md">CoordinateMappingChanged</a></td>
<td align="left">Event that is raised when any of the mappings between camera, color, and depth space change.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EY"></span>

See also  
========  

<span id="ID4E1"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CoordinateMapper Class
RLTitle : CoordinateMapper Class
KeywordK : CoordinateMapper class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.CoordinateMapper
KeywordF : CoordinateMapper
KeywordF : WindowsPreview.Kinect.CoordinateMapper
KeywordA : T:WindowsPreview.Kinect.CoordinateMapper
AssetID : T:WindowsPreview.Kinect.CoordinateMapper
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper
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
