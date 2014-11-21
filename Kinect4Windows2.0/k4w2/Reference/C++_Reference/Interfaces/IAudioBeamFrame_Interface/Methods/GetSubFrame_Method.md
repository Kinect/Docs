IAudioBeamFrame::GetSubFrame Method  
===================================  

Gets the subframe of an AudioBeamFrame by index. <span id="syntaxSection"></span>

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
HRESULT GetSubFrame(  
         UINT32 subFrameIndex,  
         IAudioBeamSubFrame **audioBeamSubFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*subFrameIndex*    
Type: UINT32  
The sub index frame number  

*audioBeamSubFrame*    
Type: IAudioBeamSubFrame  
[out] The subframe.  

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
TOCTitle : GetSubFrame Method
RLTitle : IAudioBeamFrame::GetSubFrame Method
KeywordK : GetSubFrame method
KeywordK : IAudioBeamFrame::GetSubFrame method
KeywordF : IAudioBeamFrame::GetSubFrame
KeywordF : GetSubFrame
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame.GetSubFrame(UINT32,IAudioBeamSubFrame@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrame.GetSubFrame(UINT32,IAudioBeamSubFrame@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrame.GetSubFrame(UINT32,IAudioBeamSubFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame::GetSubFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
