CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer Method  
=============================================================  

Maps a frame from depth space to color space. <span id="syntaxSection"></span>

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
void MapDepthFrameToColorSpaceUsingIBuffer(  
         IBuffer^ depthFrameData,  
         out Array&lt;<a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a>&gt;^ colorSpacePoints  
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
<td align="left"><pre><code>public void MapDepthFrameToColorSpaceUsingIBuffer (  
         IBufferdepthFrameData,  
         out Array&lt;<a href="../../ColorSpacePoint_Structure.md">ColorSpacePoint</a>&gt;[] colorSpacePoints  
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
<td align="left"><pre><code>coordinateMapper.mapDepthFrameToColorSpaceUsingIBuffer(depthFrameData, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrameData*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The depth frame data.  

*colorSpacePoints*    
Type: [ColorSpacePoint](../../ColorSpacePoint_Structure.md)  
The mapped array of points in color space.  

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
TOCTitle : MapDepthFrameToColorSpaceUsingIBuffer Method
RLTitle : CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer Method
KeywordK : MapDepthFrameToColorSpaceUsingIBuffer method
KeywordK : CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer
KeywordF : CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer
KeywordF : MapDepthFrameToColorSpaceUsingIBuffer
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.ColorSpacePoint[]@)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.ColorSpacePoint[]@)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.ColorSpacePoint[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapDepthFrameToColorSpaceUsingIBuffer
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
