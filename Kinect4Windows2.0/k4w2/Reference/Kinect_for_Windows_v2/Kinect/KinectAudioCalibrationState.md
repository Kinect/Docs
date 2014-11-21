KinectAudioCalibrationState Enumeration  
=======================================  

Specifies the Kinect for Windows sensor audio calibration states. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public enum class KinectAudioCalibrationState</code></pre></td>
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
<td align="left"><pre><code>public enum KinectAudioCalibrationState</code></pre></td>
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
<td align="left"><pre><code>var kinectAudioCalibrationState = WindowsPreview.Kinect.KinectAudioCalibrationState.calibrated;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E3"></span>

Members  
=======  

| Member                  | Value | Description                                |
|-------------------------|-------|--------------------------------------------|
| **Calibrated**          | 2     | Sensor audio is calibrated.                |
| **CalibrationRequired** | 1     | Sensor audio needs to be calibrated.       |
| **Unknown**             | 0     | Sensor audio calibration state is unknown. |

<span id="remarks"></span>

Remarks  
=======  

Note that the audio calibration state is always Calibrated for Kinect for Windows apps. This enumeration is included to support cross-compilation with the Xbox SDK.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EFB"></span>

See also  
========  

<span id="ID4EHB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectAudioCalibrationState Enumeration
RLTitle : KinectAudioCalibrationState Enumeration
KeywordK : KinectAudioCalibrationState enumeration
KeywordK : WindowsPreview.Kinect.KinectAudioCalibrationState enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.KinectAudioCalibrationState
KeywordF : KinectAudioCalibrationState
KeywordF : WindowsPreview.Kinect.KinectAudioCalibrationState
KeywordA : T:WindowsPreview.Kinect.KinectAudioCalibrationState
AssetID : T:WindowsPreview.Kinect.KinectAudioCalibrationState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectAudioCalibrationState
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
