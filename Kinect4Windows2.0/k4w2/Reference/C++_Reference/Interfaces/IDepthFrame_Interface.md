IDepthFrame Interface  
=====================  

Represents a frame where each pixel represents the distance of the closest object seen by that pixel. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IDepthFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IDepthFrame** has the following members.  

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
<td align="left"><a href="IDepthFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">Gets a pointer to the depth frame data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the depth frame data to an unsigned array.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_DepthFrameSource_Method.md">get_DepthFrameSource</a></td>
<td align="left">Gets the source of the depth frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_DepthMaxReliableDistance.md">get_DepthMaxReliableDistance</a></td>
<td align="left">Gets the maximum reliable depth of the depth frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_DepthMinReliableDistance.md">get_DepthMinReliableDistance</a></td>
<td align="left">Gets the minimum reliable depth of the depth frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Gets the description of the depth frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the timestamp of the depth frame.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The data for this frame is stored as 16-bit unsigned integers, where each value represents the distance in millimeters. The maximum depth distance is 8 meters, although reliability starts to degrade at around 4.5 meters. Developers can use the depth frame to build custom tracking algorithms in cases where the [IBodyFrame](IBodyFrame_Interface.md) isn’t enough.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IDepthFrame Interface
RLTitle : IDepthFrame Interface
KeywordK : IDepthFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IDepthFrame
KeywordF : Microsoft.Kinect.kinect.IDepthFrame
KeywordA : T:Microsoft.Kinect.kinect.IDepthFrame
AssetID : T:Microsoft.Kinect.kinect.IDepthFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
