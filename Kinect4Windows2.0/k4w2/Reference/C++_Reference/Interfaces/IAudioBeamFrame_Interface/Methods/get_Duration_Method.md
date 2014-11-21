IAudioBeamFrame::get\_Duration Method  
=====================================  

Gets the duration of the audio beam frame. <span id="syntaxSection"></span>

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
HRESULT get_Duration(  
         TIMESPAN *duration  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*duration*    
Type: TIMESPAN  
[out] The timestamp of the audio beam frame.  

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
TOCTitle : get_Duration Method
RLTitle : IAudioBeamFrame::get_Duration Method
KeywordK : get_Duration method
KeywordK : IAudioBeamFrame::get_Duration method
KeywordF : IAudioBeamFrame::get_Duration
KeywordF : get_Duration
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame.get_Duration(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_Duration(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_Duration(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame::get_Duration
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
