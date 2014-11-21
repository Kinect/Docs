CoordinateMapper.MapColorFrameToDepthSpace Method  
=================================================  

Maps a frame from color space to depth space. <span id="syntaxSection"></span>

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
void MapColorFrameToDepthSpace(  
         Array&lt;uint16&gt;^ depthFrameData,  
         out Array&lt;<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a>&gt;^ depthSpacePoints  
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
<td align="left"><pre><code>public void MapColorFrameToDepthSpace (  
         Array&lt;UInt16&gt;[] depthFrameData,  
         out Array&lt;<a href="../../DepthSpacePoint_Structure.md">DepthSpacePoint</a>&gt;[] depthSpacePoints  
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
<td align="left"><pre><code>coordinateMapper.mapColorFrameToDepthSpace(depthFrameData, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrameData*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

The depth frame data.  

*depthSpacePoints*    
Type: [DepthSpacePoint](../../DepthSpacePoint_Structure.md)  
The mapped array of points in depth space.  

<span id="remarks"></span>

Remarks  
=======  

Allocate the **depthSpacePoints** array before calling this method. It should have the same number of elements as the color frame has pixels (1920px by 1080px). Each entry in the filled **depthSpacePoints** array contains the depth point to which the corresponding pixel belongs.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EMB"></span>

See also  
========  

<span id="ID4EOB"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MapColorFrameToDepthSpace Method
RLTitle : CoordinateMapper.MapColorFrameToDepthSpace Method
KeywordK : MapColorFrameToDepthSpace method
KeywordK : CoordinateMapper.MapColorFrameToDepthSpace method
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapColorFrameToDepthSpace
KeywordF : CoordinateMapper.MapColorFrameToDepthSpace
KeywordF : MapColorFrameToDepthSpace
KeywordF : WindowsPreview.Kinect.CoordinateMapper.MapColorFrameToDepthSpace(System.UInt16[],WindowsPreview.Kinect.DepthSpacePoint[]@)
KeywordA : M:WindowsPreview.Kinect.CoordinateMapper.MapColorFrameToDepthSpace(System.UInt16[],WindowsPreview.Kinect.DepthSpacePoint[]@)
AssetID : M:WindowsPreview.Kinect.CoordinateMapper.MapColorFrameToDepthSpace(System.UInt16[],WindowsPreview.Kinect.DepthSpacePoint[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.MapColorFrameToDepthSpace
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
