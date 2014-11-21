IInfraredFrame Interface  
========================  

Represents a frame that provides view of the scene that looks just like a black and white photograph, but is actively lit, so brightness is consistent regardless of location and room brightness. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IInfraredFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IInfraredFrame** has the following members.  

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
<td align="left"><a href="IInfraredFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">Gets a pointer to the infrared frame data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the infrared frame data to an unsigned short array.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the infrared frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrame_Interface/Methods/get_InfraredFrameSource.md">get_InfraredFrameSource</a></td>
<td align="left">Gets the source of the infrared frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the source of the infrared frame.</td>
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

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IInfraredFrame Interface
RLTitle : IInfraredFrame Interface
KeywordK : IInfraredFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IInfraredFrame
KeywordF : Microsoft.Kinect.kinect.IInfraredFrame
KeywordA : T:Microsoft.Kinect.kinect.IInfraredFrame
AssetID : T:Microsoft.Kinect.kinect.IInfraredFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
