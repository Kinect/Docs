AudioBeamSubFrame Class  
=======================  

Represents an audio beam sub frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class AudioBeamSubFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioBeamSubFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var audioBeamSubFrame = WindowsPreview.Kinect.AudioBeamSubFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**AudioBeamSubFrame** has the following members.  

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
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/AudioBeamMode_Property.md">AudioBeamMode</a></td>
<td align="left">Gets the audio beam mode.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/AudioBodyCorrelations.md">AudioBodyCorrelations</a></td>
<td align="left">Acquires the list of the AudioBodyCorrelation objects available in this subframe.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/BeamAngle_Property.md">BeamAngle</a></td>
<td align="left">Gets the angle (in radians) of the audio beam, which is the direction that the sensor is actively listening.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/BeamAngleConfidence_Property.md">BeamAngleConfidence</a></td>
<td align="left">Gets the confidence in the beam angle; the range is [0.0, 1.0], where 1 is the highest possible confidence.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/Duration_Property.md">Duration</a></td>
<td align="left">Gets the duration of the audio beam sub frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/FrameLengthInBytes_Property.md">FrameLengthInBytes</a></td>
<td align="left">Gets the length of a frame in bytes.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeamSubFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the relative time of this sub frame.</td>
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
<td align="left"><a href="AudioBeamSubFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the audio beam sub frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamSubFrame_Class/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copy the audio buffer (32-bit float, mono, 16khz sample rate) into the array provided.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeamSubFrame_Class/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">Copies the frame data into the array provided.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamSubFrame_Class/Methods/LockAudioBuffer_Method.md">LockAudioBuffer</a></td>
<td align="left">Locks the audio buffer in preparation for reading the data.</td>
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
TOCTitle : AudioBeamSubFrame Class
RLTitle : AudioBeamSubFrame Class
KeywordK : AudioBeamSubFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame
KeywordF : AudioBeamSubFrame
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame
KeywordA : T:WindowsPreview.Kinect.AudioBeamSubFrame
AssetID : T:WindowsPreview.Kinect.AudioBeamSubFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamSubFrame
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
