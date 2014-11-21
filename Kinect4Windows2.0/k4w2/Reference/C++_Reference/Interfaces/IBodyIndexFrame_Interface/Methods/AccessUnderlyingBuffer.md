IBodyIndexFrame::AccessUnderlyingBuffer Method  
==============================================  

Gets a pointer to the body index frame data. <span id="syntaxSection"></span>

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
[out] Gets a pointer to the body index frame data.  

*buffer*    
Type: BYTE  
[out] The buffer to fil.  

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
TOCTitle : AccessUnderlyingBuffer Method
RLTitle : IBodyIndexFrame::AccessUnderlyingBuffer Method
KeywordK : AccessUnderlyingBuffer method
KeywordK : IBodyIndexFrame::AccessUnderlyingBuffer method
KeywordF : IBodyIndexFrame::AccessUnderlyingBuffer
KeywordF : AccessUnderlyingBuffer
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrame.AccessUnderlyingBuffer(UINT@,BYTE@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrame.AccessUnderlyingBuffer(UINT@,BYTE@)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrame.AccessUnderlyingBuffer(UINT@,BYTE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrame::AccessUnderlyingBuffer
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
