ColorFrameSource Class  
======================  

Represents a source of color frames from a KinectSensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class ColorFrameSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class ColorFrameSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var colorFrameSource = WindowsPreview.Kinect.ColorFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**ColorFrameSource** has the following members.  

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
<td align="left"><a href="ColorFrameSource_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">Gets the description of the color frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrameSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets whether the color frame source is active.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrameSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the Kinect sensor of the color frame source.</td>
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
<td align="left"><a href="ColorFrameSource_Class/Methods/CreateFrameDescription.md">CreateFrameDescription</a></td>
<td align="left">Creates a FrameDescription object for the ColorFrame of the requested format.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrameSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Creates a frame reader for the color frame source.</td>
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
<td align="left"><a href="ColorFrameSource_Class/Events/FrameCaptured_Event.md">FrameCaptured</a></td>
<td align="left">Event that is raised when the next color frame is ready to be delivered to subscribed readers.</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrameSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">ColorFrameSource</a> class changes.</td>
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
TOCTitle : ColorFrameSource Class
RLTitle : ColorFrameSource Class
KeywordK : ColorFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.ColorFrameSource
KeywordF : ColorFrameSource
KeywordF : WindowsPreview.Kinect.ColorFrameSource
KeywordA : T:WindowsPreview.Kinect.ColorFrameSource
AssetID : T:WindowsPreview.Kinect.ColorFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrameSource
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
