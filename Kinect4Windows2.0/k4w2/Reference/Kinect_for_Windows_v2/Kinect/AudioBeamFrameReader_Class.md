AudioBeamFrameReader Class  
==========================  

Represents an audio beam frame reader. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class AudioBeamFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioBeamFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var audioBeamFrameReader = WindowsPreview.Kinect.AudioBeamFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**AudioBeamFrameReader** has the following members.  

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
<td align="left"><a href="AudioBeamFrameReader_Class/Properties/AudioSource_Property.md">AudioSource</a></td>
<td align="left">Gets the audio source of the frame reader.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameReader_Class/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">Gets or sets a boolean that indicates if this reader is paused.</td>
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
<td align="left"><a href="AudioBeamFrameReader_Class/Methods/AcquireLatestBeamFrames.md">AcquireLatestBeamFrames</a></td>
<td align="left">Gets the latest audio beam frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameReader_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Closes and releases system resources associated with the audio beam frame reader.</td>
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
<td align="left"><a href="AudioBeamFrameReader_Class/Events/FrameArrived_Event.md">FrameArrived</a></td>
<td align="left">Event that fires whenever a frame is captured.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameReader_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">AudioBeamFrameReader</a> class changes.</td>
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
TOCTitle : AudioBeamFrameReader Class
RLTitle : AudioBeamFrameReader Class
KeywordK : AudioBeamFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader
KeywordF : AudioBeamFrameReader
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader
KeywordA : T:WindowsPreview.Kinect.AudioBeamFrameReader
AssetID : T:WindowsPreview.Kinect.AudioBeamFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameReader
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
