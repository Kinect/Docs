IAudioBeamSubFrame::GetAudioBodyCorrelation Method  
==================================================  

Returns the AudioBodyCorrelation associated with the sub frame which contains a body tracking id. <span id="syntaxSection"></span>

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
HRESULT GetAudioBodyCorrelation(  
         UINT index,  
         IAudioBodyCorrelation **ppAudioBodyCorrelation  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*index*    
Type: UINT  
[in] the index of the sub frame that contains the AudioBodyCorrelation.  

*ppAudioBodyCorrelation*    
Type: IAudioBodyCorrelation  
[out] Pointer to the AudioBodyCorrelation associated with the sub frame.  

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
TOCTitle : GetAudioBodyCorrelation Method
RLTitle : IAudioBeamSubFrame::GetAudioBodyCorrelation Method
KeywordK : GetAudioBodyCorrelation method
KeywordK : IAudioBeamSubFrame::GetAudioBodyCorrelation method
KeywordF : IAudioBeamSubFrame::GetAudioBodyCorrelation
KeywordF : GetAudioBodyCorrelation
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.GetAudioBodyCorrelation(UINT,IAudioBodyCorrelation@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.GetAudioBodyCorrelation(UINT,IAudioBodyCorrelation@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.GetAudioBodyCorrelation(UINT,IAudioBodyCorrelation@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::GetAudioBodyCorrelation
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
