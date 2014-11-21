ILongExposureInfraredFrame::AccessUnderlyingBuffer Method  
=========================================================  

Gets a pointer to the long exposure infrared frame data. <span id="syntaxSection"></span>

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
         UINT16 **buffer  
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
Type: UINT16  
[out] When this method returns, contains the pointer to the long exposure frame data.  

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
RLTitle : ILongExposureInfraredFrame::AccessUnderlyingBuffer Method
KeywordK : AccessUnderlyingBuffer method
KeywordK : ILongExposureInfraredFrame::AccessUnderlyingBuffer method
KeywordF : ILongExposureInfraredFrame::AccessUnderlyingBuffer
KeywordF : AccessUnderlyingBuffer
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrame.AccessUnderlyingBuffer(UINT@,UINT16@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrame.AccessUnderlyingBuffer(UINT@,UINT16@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrame.AccessUnderlyingBuffer(UINT@,UINT16@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrame::AccessUnderlyingBuffer
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
