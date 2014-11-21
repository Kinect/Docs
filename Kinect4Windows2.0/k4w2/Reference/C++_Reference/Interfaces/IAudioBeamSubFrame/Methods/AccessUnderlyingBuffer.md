IAudioBeamSubFrame::AccessUnderlyingBuffer Method  
=================================================  

Returns a pointer to audio beam sub frame data. <span id="syntaxSection"></span>

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
HRESULT AccessUnderlyingBuffer(  
         UINT *capacity,  
         BYTE **buffer  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[out] When this method returns, contains the size of the frame data buffer in bytes.  

*buffer*    
Type: BYTE  
[out] When this method returns, contains the pointer to the frame data.  

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
TOCTitle : AccessUnderlyingBuffer Method
RLTitle : IAudioBeamSubFrame::AccessUnderlyingBuffer Method
KeywordK : AccessUnderlyingBuffer method
KeywordK : IAudioBeamSubFrame::AccessUnderlyingBuffer method
KeywordF : IAudioBeamSubFrame::AccessUnderlyingBuffer
KeywordF : AccessUnderlyingBuffer
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.AccessUnderlyingBuffer(UINT@,BYTE@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.AccessUnderlyingBuffer(UINT@,BYTE@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.AccessUnderlyingBuffer(UINT@,BYTE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::AccessUnderlyingBuffer
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
