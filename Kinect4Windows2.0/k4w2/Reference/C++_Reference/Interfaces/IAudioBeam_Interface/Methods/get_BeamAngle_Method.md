IAudioBeam::get\_BeamAngle Method  
=================================  

Gets the beam angle, which is the direction that the sensor is actively listening. <span id="syntaxSection"></span>

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
HRESULT get_BeamAngle(  
         float *beamAngle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*beamAngle*    
Type: float  
[out] The beam angle.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

This is a value in radians between -0.872665 and +0.872665 radians (-50 and +50 in degrees) in .087 radian (5 degree) increments.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_BeamAngle Method
RLTitle : IAudioBeam::get_BeamAngle Method
KeywordK : get_BeamAngle method
KeywordK : IAudioBeam::get_BeamAngle method
KeywordF : IAudioBeam::get_BeamAngle
KeywordF : get_BeamAngle
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.get_BeamAngle(float@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.get_BeamAngle(float@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.get_BeamAngle(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::get_BeamAngle
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
