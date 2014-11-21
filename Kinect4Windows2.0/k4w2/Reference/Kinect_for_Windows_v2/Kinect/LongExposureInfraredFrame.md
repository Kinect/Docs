LongExposureInfraredFrame Class  
===============================  

Represents a long exposure infrared frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class LongExposureInfraredFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class LongExposureInfraredFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var longExposureInfraredFrame = WindowsPreview.Kinect.LongExposureInfraredFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**LongExposureInfraredFrame** has the following members.  

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
<td align="left"><a href="LongExposureInfraredFrame/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">Gets the description of the long exposure infrared frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="LongExposureInfraredFrame/Properties/LongExposureInfraredFrameS.md">LongExposureInfraredFrameSource</a></td>
<td align="left">Gets the long exposure infrared frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="LongExposureInfraredFrame/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the timestamp of the long exposure infrared frame.</td>
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
<td align="left"><a href="LongExposureInfraredFrame/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the long exposure infrared frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="LongExposureInfraredFrame/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the long exposure frame data into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="LongExposureInfraredFrame/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">Copies the long exposure frame data into the buffer provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="LongExposureInfraredFrame/Methods/LockImageBuffer_Method.md">LockImageBuffer</a></td>
<td align="left">Locks the buffer so the data can be read.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

This frame is similar to the [InfraredFrame](InfraredFrame_Class.md), except it has been exposed over a longer period of time. The result is a higher quality image, with less noise, at the expense of some motion blur for objects that are moving.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EFB"></span>

See also  
========  

<span id="ID4EHB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : LongExposureInfraredFrame Class
RLTitle : LongExposureInfraredFrame Class
KeywordK : LongExposureInfraredFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.LongExposureInfraredFrame
KeywordF : LongExposureInfraredFrame
KeywordF : WindowsPreview.Kinect.LongExposureInfraredFrame
KeywordA : T:WindowsPreview.Kinect.LongExposureInfraredFrame
AssetID : T:WindowsPreview.Kinect.LongExposureInfraredFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.LongExposureInfraredFrame
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
