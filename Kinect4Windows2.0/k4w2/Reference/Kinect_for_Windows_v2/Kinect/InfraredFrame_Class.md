InfraredFrame Class  
===================  

Represents a frame that provides a view of the scene that looks just like a black and white photograph, but is actively lit, so brightness is consistent regardless of location and room brightness. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class InfraredFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class InfraredFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var infraredFrame = WindowsPreview.Kinect.InfraredFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**InfraredFrame** has the following members.  

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
<td align="left"><a href="InfraredFrame_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">Gets the description of the infrared frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrame_Class/Properties/InfraredFrameSource_Property.md">InfraredFrameSource</a></td>
<td align="left">Gets the source of the infrared frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InfraredFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the timestamp of the infrared frame.</td>
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
<td align="left"><a href="InfraredFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the infrared frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrame_Class/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the infrared frame data into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InfraredFrame_Class/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">Copies the infrared frame data into the memory location provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrame_Class/Methods/LockImageBuffer_Method.md">LockImageBuffer</a></td>
<td align="left">Gives an app access to the underlying buffer used by the system to store this frame's data.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The infrared frame is great for computer vision algorithms where texture is important, such as facial recognition. Data is stored as 16-bit unsigned integers. The infrared frame is also great for green screening, tracking reflective markers, and filtering out low-return (and therefore jittery) depth pixels. Note that the infrared frame is derived from the same sensor as depth, so the images are perfectly aligned. For example, the infrared pixel at row 5 col 9 goes with the depth pixel at row 5 col 9.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : InfraredFrame Class
RLTitle : InfraredFrame Class
KeywordK : InfraredFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.InfraredFrame
KeywordF : InfraredFrame
KeywordF : WindowsPreview.Kinect.InfraredFrame
KeywordA : T:WindowsPreview.Kinect.InfraredFrame
AssetID : T:WindowsPreview.Kinect.InfraredFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.InfraredFrame
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
