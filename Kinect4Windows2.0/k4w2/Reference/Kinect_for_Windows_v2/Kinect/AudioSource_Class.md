AudioSource Class  
=================  

Represents an audio frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class AudioSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var audioSource = WindowsPreview.Kinect.AudioSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**AudioSource** has the following members.  

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
<td align="left"><a href="AudioSource_Class/Properties/AudioBeams_Property.md">AudioBeams</a></td>
<td align="left">Gets the audio beams.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Properties/AudioCalibrationState.md">AudioCalibrationState</a></td>
<td align="left">Gets a value that indicates whether or not the Kinect Sensor is properly calibrated to listen for audio. This API is not implemented in the Kinect for Windows v2 SDK and will always return Calibrated. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets the current activity status of this source.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the parent sensor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioSource_Class/Properties/MaxSubFrameCount_Property.md">MaxSubFrameCount</a></td>
<td align="left">Gets the maximum number of sub frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Properties/SubFrameDuration_Property.md">SubFrameDuration</a></td>
<td align="left">Gets the sub frame duration.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioSource_Class/Properties/SubFrameLengthInBytes.md">SubFrameLengthInBytes</a></td>
<td align="left">Gets the sub frame length (in bytes).</td>
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
<td align="left"><a href="AudioSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Opens a new stream reader. This reader must be disposed.</td>
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
<td align="left"><a href="AudioSource_Class/Events/FrameCaptured_Event.md">FrameCaptured</a></td>
<td align="left">Event that fires whenever a frame is captured.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">AudioSource</a> class changes.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EZ"></span>

See also  
========  

<span id="ID4E2"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioSource Class
RLTitle : AudioSource Class
KeywordK : AudioSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioSource
KeywordF : AudioSource
KeywordF : WindowsPreview.Kinect.AudioSource
KeywordA : T:WindowsPreview.Kinect.AudioSource
AssetID : T:WindowsPreview.Kinect.AudioSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioSource
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
