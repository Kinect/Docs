MultiSourceFrameReader Class  
============================  

Represents a reader for multi source frames. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class MultiSourceFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class MultiSourceFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var multiSourceFrameReader = WindowsPreview.Kinect.MultiSourceFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**MultiSourceFrameReader** has the following members.  

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
<td align="left"><a href="MultiSourceFrameReader/Properties/FrameSourceTypes_Property.md">FrameSourceTypes</a></td>
<td align="left">Gets the types of frames being read by the multi source frame reader.</td>
</tr>
<tr class="even">
<td align="left"><a href="MultiSourceFrameReader/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">Gets or sets whether the multi source frame reader is paused.</td>
</tr>
<tr class="odd">
<td align="left"><a href="MultiSourceFrameReader/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the Kinect sensor associated with the reader.</td>
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
<td align="left"><a href="MultiSourceFrameReader/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">Gets the most recent multi source frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="MultiSourceFrameReader/Methods/Close_Method.md">Close</a></td>
<td align="left">Closes and releases system resources associated with the multi-source frame reader.</td>
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
<td align="left"><a href="MultiSourceFrameReader/Events/MultiSourceFrameArrived.md">MultiSourceFrameArrived</a></td>
<td align="left">Event that fires whenever a frame is captured.</td>
</tr>
<tr class="even">
<td align="left"><a href="MultiSourceFrameReader/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">MultiSourceFrameReader</a> changes.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MultiSourceFrameReader Class
RLTitle : MultiSourceFrameReader Class
KeywordK : MultiSourceFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.MultiSourceFrameReader
KeywordF : MultiSourceFrameReader
KeywordF : WindowsPreview.Kinect.MultiSourceFrameReader
KeywordA : T:WindowsPreview.Kinect.MultiSourceFrameReader
AssetID : T:WindowsPreview.Kinect.MultiSourceFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.MultiSourceFrameReader
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
