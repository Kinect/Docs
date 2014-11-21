KinectAudioCalibrationState Enumeration  
=======================================  

Enumerates the calibration states of the audio sensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectAudioCalibrationState  
{  
    KinectAudioCalibrationState_Unknown = 0,  
    KinectAudioCalibrationState_CalibrationRequired = 1,  
    KinectAudioCalibrationState_Calibrated = 2  
} KinectAudioCalibrationState, KinectAudioCalibrationState_Unknown, KinectAudioCalibrationState_CalibrationRequired, KinectAudioCalibrationState_Calibrated;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant                                         | Description                            |
|--------------------------------------------------|----------------------------------------|
| KinectAudioCalibrationState\_Unknown             | The calibration state is unknown.      |
| KinectAudioCalibrationState\_CalibrationRequired | The audio sensor requires calibration. |
| KinectAudioCalibrationState\_Calibrated          | The audio sensor is calibrated.        |

<span id="remarks"></span>

Remarks  
=======  

Note that the audio calibration state is always Calibrated for Kinect for Windows apps. This enumeration is included to support cross-compilation with the Xbox SDK.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectAudioCalibrationState Enumeration
RLTitle : KinectAudioCalibrationState Enumeration
KeywordK : KinectAudioCalibrationState enumeration
HelpPriority : 2
KeywordF : KinectAudioCalibrationState
KeywordF : Microsoft.Kinect.kinect.KinectAudioCalibrationState
KeywordA : T:Microsoft.Kinect.kinect.KinectAudioCalibrationState
AssetID : T:Microsoft.Kinect.kinect.KinectAudioCalibrationState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectAudioCalibrationState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
