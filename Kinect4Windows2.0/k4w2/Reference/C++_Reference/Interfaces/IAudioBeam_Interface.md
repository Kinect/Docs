IAudioBeam Interface  
====================  

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
<td align="left"><pre><code>interface IAudioBeam : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioBeam** has the following members.  

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
<td align="left"><a href="IAudioBeam_Interface/Methods/get_AudioBeamMode_Method.md">get_AudioBeamMode</a></td>
<td align="left">Gets the audio beam mode, which detemines the type of beam angle.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_AudioSource_Method.md">get_AudioSource</a></td>
<td align="left">Gets the audio source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_BeamAngle_Method.md">get_BeamAngle</a></td>
<td align="left">Gets the beam angle, which is the direction that the sensor is actively listening.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_BeamAngleConfidence.md">get_BeamAngleConfidence</a></td>
<td align="left">Gets the confidence in the beam angle; the range is [0.0, 1.0], where 1 is the highest possible confidence.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the relative time of this frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/OpenInputStream_Method.md">OpenInputStream</a></td>
<td align="left">Gets the input stream.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/put_AudioBeamMode_Method.md">put_AudioBeamMode</a></td>
<td align="left">Sets the audio beam mode, which detemines the type of beam angle.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/put_BeamAngle_Method.md">put_BeamAngle</a></td>
<td align="left">Sets the beam angle, which is the direction that the sensor is actively listening.</td>
</tr>
</tbody>
</table>

<span id="ID4ES"></span>

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
<td align="left"><a href="IAudioBeam_Interface/Methods/get_AudioBeamMode_Method.md">get_AudioBeamMode</a></td>
<td align="left">Gets the audio beam mode, which detemines the type of beam angle.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_AudioSource_Method.md">get_AudioSource</a></td>
<td align="left">Gets the audio source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_BeamAngle_Method.md">get_BeamAngle</a></td>
<td align="left">Gets the beam angle, which is the direction that the sensor is actively listening.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_BeamAngleConfidence.md">get_BeamAngleConfidence</a></td>
<td align="left">Gets the confidence in the beam angle; the range is [0.0, 1.0], where 1 is the highest possible confidence.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the relative time of this frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/OpenInputStream_Method.md">OpenInputStream</a></td>
<td align="left">Gets the input stream.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/put_AudioBeamMode_Method.md">put_AudioBeamMode</a></td>
<td align="left">Sets the audio beam mode, which detemines the type of beam angle.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/put_BeamAngle_Method.md">put_BeamAngle</a></td>
<td align="left">Sets the beam angle, which is the direction that the sensor is actively listening.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IAudioBeam Interface
RLTitle : IAudioBeam Interface
KeywordK : IAudioBeam interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioBeam
KeywordF : Microsoft.Kinect.kinect.IAudioBeam
KeywordA : T:Microsoft.Kinect.kinect.IAudioBeam
AssetID : T:Microsoft.Kinect.kinect.IAudioBeam
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
