AudioBeam Class  
===============  

Represents an audio beam. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class AudioBeam sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioBeam : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var audioBeam = WindowsPreview.Kinect.AudioBeam;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**AudioBeam** has the following members.  

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
<td align="left"><a href="AudioBeam_Class/Properties/AudioBeamMode_Property.md">AudioBeamMode</a></td>
<td align="left">Gets or sets the audio beam mode, which determines the type of beam angle.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeam_Class/Properties/AudioSource_Property.md">AudioSource</a></td>
<td align="left">Gets the audio source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeam_Class/Properties/BeamAngle_Property.md">BeamAngle</a></td>
<td align="left">Gets or sets the beam angle, which is the direction that the sensor is actively listening.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeam_Class/Properties/BeamAngleConfidence_Property.md">BeamAngleConfidence</a></td>
<td align="left">Gets the confidence in the beam angle; the range is [0.0, 1.0], where 1 is the highest possible confidence.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeam_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">Gets the relative time of this frame.</td>
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
<td align="left"><a href="AudioBeam_Class/Methods/OpenInputStream_Method.md">OpenInputStream</a></td>
<td align="left">Opens the input stream. The input stream is a mono 32-bit IEEE floating point PCM stream sampled at 16 kHz. Typical PCM values will be between -1 and +1.</td>
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
<td align="left"><a href="AudioBeam_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">AudioBeam</a> class changes.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

To capture audio, the sensor receives sounds from every direction. However, like the cone of light from a lighthouse where the light is the brightest, the audio capture hardware has an imaginary cone that is able to capture audio signals the best. Audio waves that propagate through the length of the cone can be separated from audio waves that travel across the cone. If you point the cone in the direction of the audio that your application is most interested in capturing, you can improve the ability to capture and separate that audio source from other competing audio sources. Therefore, use the beam angle to set the direction of the imaginary cone to improve your ability to capture a specific audio source.  

Similar to the sound source angle, the beam angle is also defined in the x-z plane of the sensor perpendicular to the z-axis. The beam angle and the sound source angle are both updated continuously once the sensor has started streaming audio data (when the Start method is called).  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioBeam Class
RLTitle : AudioBeam Class
KeywordK : AudioBeam class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioBeam
KeywordF : AudioBeam
KeywordF : WindowsPreview.Kinect.AudioBeam
KeywordA : T:WindowsPreview.Kinect.AudioBeam
AssetID : T:WindowsPreview.Kinect.AudioBeam
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeam
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
