IBodyIndexFrame Interface  
=========================  

Represents a frame that is computed based on the depth image. This image tells you which depth or infrared pixels belong to tracked people and which belong to the background. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyIndexFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyIndexFrame** has the following members.  

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
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">Gets a pointer to the body index frame data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the frame data into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/get_BodyIndexFrameSource.md">get_BodyIndexFrameSource</a></td>
<td align="left">Gets the source of the body index frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the body index frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the timestamp of the body index frame.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The pixel values in this frame are 8-bit unsigned integers, where 0-5 map directly to the BodyData index in the [IBodyFrame](IBodyFrame_Interface.md). Values greater than the value obtained from [get\_BodyCount](IBodyFrameSource_Interface/Methods/get_BodyCount_Method.md) indicate the pixel is part of the background, not associated with a tracked body. This frame is useful for green screening applications, or any scenario where you want to display the silhouette of the user. It also provides a good starting bounds for custom depth algorithms.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IBodyIndexFrame Interface
RLTitle : IBodyIndexFrame Interface
KeywordK : IBodyIndexFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyIndexFrame
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrame
KeywordA : T:Microsoft.Kinect.kinect.IBodyIndexFrame
AssetID : T:Microsoft.Kinect.kinect.IBodyIndexFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
