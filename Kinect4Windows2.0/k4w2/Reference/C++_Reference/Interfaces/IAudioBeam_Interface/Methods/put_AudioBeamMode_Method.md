IAudioBeam::put\_AudioBeamMode Method  
=====================================  

Sets the audio beam mode, which detemines the type of beam angle. <span id="syntaxSection"></span>

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
HRESULT put_AudioBeamMode(  
         <a href="../../../Enumerations/AudioBeamMode_Enumeration.md">AudioBeamMode</a> audioBeamMode  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioBeamMode*    
Type: [AudioBeamMode](../../../Enumerations/AudioBeamMode_Enumeration.md)  
The audio beam mode.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

If the mode is set to AudioBeamMode\_Automatic, the beam angle actively follows the direction of sound source. If the mode is set to AudioBeamMode\_Manual, the beam angle is fixed at the value set by calling [put\_BeamAngle](put_BeamAngle_Method.md).  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : put_AudioBeamMode Method
RLTitle : IAudioBeam::put_AudioBeamMode Method
KeywordK : put_AudioBeamMode method
KeywordK : IAudioBeam::put_AudioBeamMode method
KeywordF : IAudioBeam::put_AudioBeamMode
KeywordF : put_AudioBeamMode
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.put_AudioBeamMode(Microsoft.Kinect.kinect.AudioBeamMode)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.put_AudioBeamMode(Microsoft.Kinect.kinect.AudioBeamMode)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.put_AudioBeamMode(Microsoft.Kinect.kinect.AudioBeamMode)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::put_AudioBeamMode
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
