IBodyFrame Interface  
====================  

Represents a frame that contains all the computed real-time tracking information about people that are in view of the sensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyFrame** has the following members.  

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
<td align="left"><a href="IBodyFrame_Interface/Methods/get_BodyFrameSource_Method.md">get_BodyFrameSource</a></td>
<td align="left">Gets the body frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrame_Interface/Methods/get_FloorClipPlane_Method.md">get_FloorClipPlane</a></td>
<td align="left">Gets the floor clip plane.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the timestamp of the body frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrame_Interface/Methods/GetAndRefreshBodyData_Method.md">GetAndRefreshBodyData</a></td>
<td align="left">Gets refreshed body data.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The computed data provided by this frame type includes skeletal joints and orientations, hand states, facial expressions, and more for up to 6 people at a time. These tracking features provide a great baseline for getting started with human interaction in your app.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IBodyFrame Interface
RLTitle : IBodyFrame Interface
KeywordK : IBodyFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyFrame
KeywordF : Microsoft.Kinect.kinect.IBodyFrame
KeywordA : T:Microsoft.Kinect.kinect.IBodyFrame
AssetID : T:Microsoft.Kinect.kinect.IBodyFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
