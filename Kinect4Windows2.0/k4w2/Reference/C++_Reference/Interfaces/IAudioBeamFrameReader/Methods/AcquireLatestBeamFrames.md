IAudioBeamFrameReader::AcquireLatestBeamFrames Method  
=====================================================  

Gets the latest audio beam frames. <span id="syntaxSection"></span>

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
HRESULT AcquireLatestBeamFrames(  
         IAudioBeamFrameList **audioBeamFrameList  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioBeamFrameList*    
Type: IAudioBeamFrameList  
[out] The latest audio beam frames.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code. Returns E\_PENDING when there is no new frame ready yet. This can occur when polling too frequently.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AcquireLatestBeamFrames Method
RLTitle : IAudioBeamFrameReader::AcquireLatestBeamFrames Method
KeywordK : AcquireLatestBeamFrames method
KeywordK : IAudioBeamFrameReader::AcquireLatestBeamFrames method
KeywordF : IAudioBeamFrameReader::AcquireLatestBeamFrames
KeywordF : AcquireLatestBeamFrames
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrameReader.AcquireLatestBeamFrames(IAudioBeamFrameList@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrameReader.AcquireLatestBeamFrames(IAudioBeamFrameList@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrameReader.AcquireLatestBeamFrames(IAudioBeamFrameList@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrameReader::AcquireLatestBeamFrames
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
