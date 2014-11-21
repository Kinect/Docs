KinectSensor.OpenMultiSourceFrameReader Method  
==============================================  

Creates a frame reader for the multiple frame sources. <span id="syntaxSection"></span>

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
<a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>^ OpenMultiSourceFrameReader(  
         <a href="../../FrameSourceTypes_Enumeration.md">FrameSourceTypes</a> enabledFrameSourceTypes  
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
<td align="left"><pre><code>public <a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>OpenMultiSourceFrameReader (  
         <a href="../../FrameSourceTypes_Enumeration.md">FrameSourceTypes</a> enabledFrameSourceTypes  
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
<td align="left"><pre><code>var multiSourceFrameReader = kinectSensor.openMultiSourceFrameReader(enabledFrameSourceTypes);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EJ"></span>
#### Parameters  

*enabledFrameSourceTypes*    
Type: [FrameSourceTypes](../../FrameSourceTypes_Enumeration.md)  
 The frame source types.  

<span id="ID4ES"></span>
#### Return value  

Type: [MultiSourceFrameReader](../../MultiSourceFrameReader_Class.md)  
 A new reader for the multiple frame source.  

<span id="remarks"></span>

Remarks  
=======  

The *enabledFrameSourceTypes* can be one or more of the following values:  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Value</th>
<th align="left">Meaning</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">FrameSourceTypes::Color</td>
<td align="left">Include Color Frames in this MultiSourceFrameReader.  
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">MultiSourceFrameReader will align to the slowest framerate of any subscribed source. In lowlight scenarios, the color stream may drop to 15 FPS. If this happens, and MultiSourceFrameReader is subscribed to color as one of its subscribed sources, the rate of delivered frames will drop to 15 FPS for the entire instance of this MultiSourceFrameReader</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes::Infrared</td>
<td align="left">Include infrared frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes::Audio</td>
<td align="left">Audio is not supported for MultiSourceFrameReader. Including this source will cause this method to fail.</td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes::LongExposureInfrared</td>
<td align="left">Include long exposure infrared frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes::Depth</td>
<td align="left">Include depth frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes::BodyIndex</td>
<td align="left">Include body index frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes::Body</td>
<td align="left">Include body frames in this MultiSourceFrameReader.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EPD"></span>

See also  
========  

<span id="ID4ERD"></span>
#### Reference  

[KinectSensor Class](../../KinectSensor_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenMultiSourceFrameReader Method
RLTitle : KinectSensor.OpenMultiSourceFrameReader Method
KeywordK : OpenMultiSourceFrameReader method
KeywordK : KinectSensor.OpenMultiSourceFrameReader method
KeywordF : WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader
KeywordF : KinectSensor.OpenMultiSourceFrameReader
KeywordF : OpenMultiSourceFrameReader
KeywordF : WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader(WindowsPreview.Kinect.FrameSourceTypes)
KeywordA : M:WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader(WindowsPreview.Kinect.FrameSourceTypes)
AssetID : M:WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader(WindowsPreview.Kinect.FrameSourceTypes)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader
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
