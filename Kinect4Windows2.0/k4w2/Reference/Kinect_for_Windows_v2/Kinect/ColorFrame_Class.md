ColorFrame Class  
================  

Represents a color frame from the ColorFrameSource of a KinectSensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class ColorFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class ColorFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var colorFrame = WindowsPreview.Kinect.ColorFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**ColorFrame** has the following members.  

<span id="publicpropertiesSection"></span>

Properties  
==========  

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
<td align="left"><a href="ColorFrame_Class/Properties/ColorCameraSettings_Property.md">ColorCameraSettings</a></td>
<td align="left">Gets the color camera settings of the color frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Properties/ColorFrameSource_Property.md">ColorFrameSource</a></td>
<td align="left">Gets the source of the color frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">Gets the description of the color frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Properties/RawColorImageFormat_Property.md">RawColorImageFormat</a></td>
<td align="left">Gets the format of the color frame data.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the timestamp of the color frame.</td>
</tr>
</tbody>
</table>

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
<td align="left"><a href="ColorFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the color frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Methods/CopyConvertedFrameDataToAr.md">CopyConvertedFrameDataToArray</a></td>
<td align="left">Converts the raw format into the requested format and copies the data into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Methods/CopyConvertedFrameDataToBu.md">CopyConvertedFrameDataToBuffer</a></td>
<td align="left">Converts the raw format into the requested format and copies the data into the memory location provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Methods/CopyRawFrameDataToArray.md">CopyRawFrameDataToArray</a></td>
<td align="left">Copies the raw frame data into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Methods/CopyRawFrameDataToBuffer.md">CopyRawFrameDataToBuffer</a></td>
<td align="left">Copies raw frame data into the memory location provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Methods/CreateFrameDescription.md">CreateFrameDescription</a></td>
<td align="left">Creates a FrameDescription object for the ColorFrame of the requested format.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Methods/LockRawImageBuffer_Method.md">LockRawImageBuffer</a></td>
<td align="left">Gives an app access to the underlying buffer used by the system to store this frame's data.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ColorFrame Class
RLTitle : ColorFrame Class
KeywordK : ColorFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.ColorFrame
KeywordF : ColorFrame
KeywordF : WindowsPreview.Kinect.ColorFrame
KeywordA : T:WindowsPreview.Kinect.ColorFrame
AssetID : T:WindowsPreview.Kinect.ColorFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrame
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
