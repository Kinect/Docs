IAudioBeamSubFrame::get\_BeamAngleConfidence Method  
===================================================  

Gets the confidence in the beam angle; the range is [0.0, 1.0], where 1 is the highest possible confidence. <span id="syntaxSection"></span>

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
HRESULT get_BeamAngleConfidence(  
         float *beamAngleConfidence  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*beamAngleConfidence*    
Type: float  
[out] The confidence in the beam angle.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_BeamAngleConfidence Method
RLTitle : IAudioBeamSubFrame::get_BeamAngleConfidence Method
KeywordK : get_BeamAngleConfidence method
KeywordK : IAudioBeamSubFrame::get_BeamAngleConfidence method
KeywordF : IAudioBeamSubFrame::get_BeamAngleConfidence
KeywordF : get_BeamAngleConfidence
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_BeamAngleConfidence(float@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_BeamAngleConfidence(float@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_BeamAngleConfidence(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::get_BeamAngleConfidence
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
