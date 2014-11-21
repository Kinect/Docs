BodyFrameSource Class  
=====================  

Represents a source of body frames from a KinectSensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class BodyFrameSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class BodyFrameSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var bodyFrameSource = WindowsPreview.Kinect.BodyFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**BodyFrameSource** has the following members.  

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
<td align="left"><a href="BodyFrameSource_Class/Properties/BodyCount_Property.md">BodyCount</a></td>
<td align="left">Gets the number of bodies.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrameSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets whether the body frame source is active.</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyFrameSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the KinectSensor with which the body frame source is associated.</td>
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
<td align="left"><a href="BodyFrameSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the body frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrameSource_Class/Methods/OverrideHandTracking_Method.md">OverrideHandTracking</a></td>
<td align="left">Overloaded. Overloaded methods for OverrideHandTracking.</td>
</tr>
</tbody>
</table>

<span id="publiceventsSection"></span>

Events  
======  

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
<td align="left"><a href="BodyFrameSource_Class/Events/FrameCaptured_Event.md">FrameCaptured</a></td>
<td align="left">Event that is raised when the next body frame is ready to be delivered to subscribed readers.</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyFrameSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">BodyFrameSource</a> class changes.</td>
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
TOCTitle : BodyFrameSource Class
RLTitle : BodyFrameSource Class
KeywordK : BodyFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.BodyFrameSource
KeywordF : BodyFrameSource
KeywordF : WindowsPreview.Kinect.BodyFrameSource
KeywordA : T:WindowsPreview.Kinect.BodyFrameSource
AssetID : T:WindowsPreview.Kinect.BodyFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyFrameSource
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
