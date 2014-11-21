IAudioBeamSubFrame Interface  
============================  

Represents and audio beam sub frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IAudioBeamSubFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioBeamSubFrame** has the following members.  

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
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">Returns a pointer to audio beam sub frame data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Copies the infrared frame data to an unsigned short array.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_AudioBeamMode_Method.md">get_AudioBeamMode</a></td>
<td align="left">Gets the audio beam mode, which detemines the type of beam angle.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get.md">get_AudioBodyCorrelationCount</a></td>
<td align="left">Gets a collection of audio body correlations.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_BeamAngle_Method.md">get_BeamAngle</a></td>
<td align="left">Gets the beam angle, which is the direction that the sensor is actively listening.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_BeamAngleConfidence.md">get_BeamAngleConfidence</a></td>
<td align="left">Gets the confidence in the beam angle; the range is [0.0, 1.0], where 1 is the highest possible confidence.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_Duration_Method.md">get_Duration</a></td>
<td align="left">Gets the duration of the audio beam sub frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_FrameLengthInBytes.md">get_FrameLengthInBytes</a></td>
<td align="left">Gets the length of a frame in bytes.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Gets the relative time of this sub frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/GetAudioBodyCorrelation.md">GetAudioBodyCorrelation</a></td>
<td align="left">Returns the AudioBodyCorrelation associated with the sub frame which contains a body tracking id.</td>
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
TOCTitle : IAudioBeamSubFrame Interface
RLTitle : IAudioBeamSubFrame Interface
KeywordK : IAudioBeamSubFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioBeamSubFrame
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame
KeywordA : T:Microsoft.Kinect.kinect.IAudioBeamSubFrame
AssetID : T:Microsoft.Kinect.kinect.IAudioBeamSubFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
