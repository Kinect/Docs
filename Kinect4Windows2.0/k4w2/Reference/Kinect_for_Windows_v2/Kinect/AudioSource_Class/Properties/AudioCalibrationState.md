AudioSource.AudioCalibrationState Property  
==========================================  

Gets a value that indicates whether or not the Kinect Sensor is properly calibrated to listen for audio. This API is not implemented in the Kinect for Windows v2 SDK and will always return Calibrated. It is included to support cross-compilation with the Xbox SDK. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
property <a href="../../KinectAudioCalibrationState.md">KinectAudioCalibrationState</a> AudioCalibrationState {  
         <a href="../../KinectAudioCalibrationState.md">KinectAudioCalibrationState</a> get ();  
}</code></pre></td>
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
<td align="left"><pre><code>public <a href="../../KinectAudioCalibrationState.md">KinectAudioCalibrationState</a> AudioCalibrationState { get; }</code></pre></td>
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
<td align="left"><pre><code>var audioCalibrationState = audioSource.audioCalibrationState;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

Type: [KinectAudioCalibrationState](../../KinectAudioCalibrationState.md)  
A value that indicates whether or not the Kinect Sensor is properly calibrated to listen for audio.  

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

[AudioSource Class](../../AudioSource_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioCalibrationState Property
RLTitle : AudioSource.AudioCalibrationState Property
KeywordK : AudioCalibrationState property
KeywordK : AudioSource.AudioCalibrationState property
KeywordF : WindowsPreview.Kinect.AudioSource.AudioCalibrationState
KeywordF : AudioSource.AudioCalibrationState
KeywordF : AudioCalibrationState
KeywordF : WindowsPreview.Kinect.AudioSource.AudioCalibrationState
KeywordA : P:WindowsPreview.Kinect.AudioSource.AudioCalibrationState
AssetID : P:WindowsPreview.Kinect.AudioSource.AudioCalibrationState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioSource.AudioCalibrationState
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
