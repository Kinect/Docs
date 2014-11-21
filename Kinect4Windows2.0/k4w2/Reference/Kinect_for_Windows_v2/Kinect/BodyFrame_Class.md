BodyFrame Class  
===============  

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
<td align="left"><pre><code>public ref class BodyFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class BodyFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var bodyFrame = WindowsPreview.Kinect.BodyFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**BodyFrame** has the following members.  

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
<td align="left"><a href="BodyFrame_Class/Properties/BodyCount_Property.md">BodyCount</a></td>
<td align="left">Gets the body count, which is the number of bodies the system can track and thus the size of the collection that must be used to store these bodies.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrame_Class/Properties/BodyFrameSource_Property.md">BodyFrameSource</a></td>
<td align="left">Gets the source of the body frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyFrame_Class/Properties/FloorClipPlane_Property.md">FloorClipPlane</a></td>
<td align="left">Gets the floor clip plane of the body frame in hessian normal form. The (x,y,z) components are a unit vector indicating the normal of the plane, and w is the distance from the plane to the origin in meters.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the timestamp of the body frame.</td>
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
<td align="left"><a href="BodyFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the body frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrame_Class/Methods/GetAndRefreshBodyData_Method.md">GetAndRefreshBodyData</a></td>
<td align="left">Gets refreshed body data.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The computed data provided by this frame type includes skeletal joints and orientations, hand states, and more for up to 6 people at a time. These tracking features provide a great baseline for getting started with human interaction in your app.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EBB"></span>

See also  
========  

<span id="ID4EDB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : BodyFrame Class
RLTitle : BodyFrame Class
KeywordK : BodyFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.BodyFrame
KeywordF : BodyFrame
KeywordF : WindowsPreview.Kinect.BodyFrame
KeywordA : T:WindowsPreview.Kinect.BodyFrame
AssetID : T:WindowsPreview.Kinect.BodyFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyFrame
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
