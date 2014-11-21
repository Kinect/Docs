IColorFrame Interface  
=====================  

Represents a color frame for color images. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IColorFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IColorFrame** has the following members.  

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
<td align="left"><a href="IColorFrame_Interface/Methods/AccessRawUnderlyingBuffer.md">AccessRawUnderlyingBuffer</a></td>
<td align="left">Gets a pointer to the color frame data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/CopyConvertedFrameDataToAr.md">CopyConvertedFrameDataToArray</a></td>
<td align="left">Copies the color frame data converted into the requested format to a byte array.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/CopyRawFrameDataToArray.md">CopyRawFrameDataToArray</a></td>
<td align="left">Copies the raw frame data into the array provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/CreateFrameDescription.md">CreateFrameDescription</a></td>
<td align="left">Creates a FrameDescription object for the ColorFrame of the requested format.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/get_ColorCameraSettings.md">get_ColorCameraSettings</a></td>
<td align="left">Gets the color camera settings.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/get_ColorFrameSource_Method.md">get_ColorFrameSource</a></td>
<td align="left">Gets the source of the color frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the color frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/get_RawColorImageFormat.md">get_RawColorImageFormat</a></td>
<td align="left">Gets the format of the color frame data.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the timestamp of the color frame.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IColorFrame Interface
RLTitle : IColorFrame Interface
KeywordK : IColorFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IColorFrame
KeywordF : Microsoft.Kinect.kinect.IColorFrame
KeywordA : T:Microsoft.Kinect.kinect.IColorFrame
AssetID : T:Microsoft.Kinect.kinect.IColorFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
