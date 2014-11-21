IAudioBeamSubFrame::CopyFrameDataToArray Method  
===============================================  

Copies the infrared frame data to an unsigned short array. <span id="syntaxSection"></span>

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
HRESULT CopyFrameDataToArray(  
         _Pre_equal_to_(1024)UINT capacity,  
         BYTE *frameData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: \_Pre\_equal\_to\_(1024)UINT  
Size of the buffer provided.  

*frameData*    
Type: BYTE  
[out] The array to which to copy the sub frame data.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The byte array is a mono 32-bit IEEE floating point PCM stream sampled at 16 kHz. Typical PCM values will be between -1 and +1.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyFrameDataToArray Method
RLTitle : IAudioBeamSubFrame::CopyFrameDataToArray Method
KeywordK : CopyFrameDataToArray method
KeywordK : IAudioBeamSubFrame::CopyFrameDataToArray method
KeywordF : IAudioBeamSubFrame::CopyFrameDataToArray
KeywordF : CopyFrameDataToArray
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.CopyFrameDataToArray(_Pre_equal_to_(1024)UINT,BYTE@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.CopyFrameDataToArray(_Pre_equal_to_(1024)UINT,BYTE@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.CopyFrameDataToArray(_Pre_equal_to_(1024)UINT,BYTE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::CopyFrameDataToArray
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
