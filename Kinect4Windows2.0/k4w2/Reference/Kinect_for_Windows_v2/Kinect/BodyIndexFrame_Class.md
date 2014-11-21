BodyIndexFrame Class  
====================  

Represents a frame that indicates which depth or infrared pixels belong to tracked people and which do not. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class BodyIndexFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class BodyIndexFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var bodyIndexFrame = WindowsPreview.Kinect.BodyIndexFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**BodyIndexFrame** has the following members.  

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
<td align="left"><a href="BodyIndexFrame_Class/Properties/BodyIndexFrameSource.md">BodyIndexFrameSource</a></td>
<td align="left">Gets the source of the body index frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrame_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">Gets the description of the body index frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyIndexFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the timestamp of the body index frame.</td>
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
<td align="left"><a href="BodyIndexFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the body index frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrame_Class/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the body index frame data into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyIndexFrame_Class/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">Copies the body index frame data into the memory location provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrame_Class/Methods/LockImageBuffer_Method.md">LockImageBuffer</a></td>
<td align="left">Gives an app access to the underlying buffer used by the system to store this frame's data.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The pixel values in this frame are 8-bit unsigned integers, where 0-5 map directly to the BodyData index in the [BodyFrame](BodyFrame_Class.md). Values greater than the value obtained from [BodyCount](BodyFrameSource_Class/Properties/BodyCount_Property.md) indicate the pixel is part of the background, not associated with a tracked body. This frame is useful for green screening applications, or any scenario where you want to display the silhouette of the user. It also provides a good starting bounds for custom depth algorithms.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : BodyIndexFrame Class
RLTitle : BodyIndexFrame Class
KeywordK : BodyIndexFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.BodyIndexFrame
KeywordF : BodyIndexFrame
KeywordF : WindowsPreview.Kinect.BodyIndexFrame
KeywordA : T:WindowsPreview.Kinect.BodyIndexFrame
AssetID : T:WindowsPreview.Kinect.BodyIndexFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyIndexFrame
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
