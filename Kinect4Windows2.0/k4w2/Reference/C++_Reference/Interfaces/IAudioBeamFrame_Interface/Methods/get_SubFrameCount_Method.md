IAudioBeamFrame::get\_SubFrameCount Method  
==========================================  

Gets the number of audio beam sub frames. <span id="syntaxSection"></span>

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
HRESULT get_SubFrameCount(  
         UINT32 *pSubFrameCount  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pSubFrameCount*    
Type: UINT32  
[out] The number of audio beam sub frames.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

This number will be between 1 and 8, where 8 is the value you get from [get\_MaxSubFrameCount](../../IAudioSource_Interface/Methods/get_MaxSubFrameCount_Method.md). Typically an audio frame will have between 1 to 3 subframes. This number may vary from one frame to another. Only when computational resources are extremely limited Kinect Service will produce frames with a lager number of subframes (higher latency).  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_SubFrameCount Method
RLTitle : IAudioBeamFrame::get_SubFrameCount Method
KeywordK : get_SubFrameCount method
KeywordK : IAudioBeamFrame::get_SubFrameCount method
KeywordF : IAudioBeamFrame::get_SubFrameCount
KeywordF : get_SubFrameCount
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame.get_SubFrameCount(UINT32@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_SubFrameCount(UINT32@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_SubFrameCount(UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame::get_SubFrameCount
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
