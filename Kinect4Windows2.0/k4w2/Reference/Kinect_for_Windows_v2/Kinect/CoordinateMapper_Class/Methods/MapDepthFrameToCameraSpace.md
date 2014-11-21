CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer Method  
==============================================================  

Maps a frame from depth space to camera space. <span id="syntaxSection"></span>

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
void MapDepthFrameToCameraSpaceUsingIBuffer(  
         IBuffer^ depthFrameData,  
         out Array&lt;<a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a>&gt;^ cameraSpacePoints  
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
<td align="left"><pre><code>public void MapDepthFrameToCameraSpaceUsingIBuffer (  
         IBufferdepthFrameData,  
         out Array&lt;<a href="../../CameraSpacePoint_Structure.md">CameraSpacePoint</a>&gt;[] cameraSpacePoints  
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
<td align="left"><pre><code>coordinateMapper.mapDepthFrameToCameraSpaceUsingIBuffer(depthFrameData, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrameData*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The depth frame data.  

*cameraSpacePoints*    
Type: [CameraSpacePoint](../../CameraSpacePoint_Structure.md)  
The mapped array of points in camera space.  

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
TOCTitle : MapDepthFrameToCameraSpaceUsingIBuffer Method
RLTitle : CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer Method
KeywordK : MapDepthFrameToCameraSpaceUsingIBuffer method
KeywordK : CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer
KeywordF : CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer
KeywordF : MapDepthFrameToCameraSpaceUsingIBuffer
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.CameraSpacePoint[]@)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.CameraSpacePoint[]@)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.CameraSpacePoint[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToCameraSpaceUsingIBuffer
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
