IDepthFrame::CopyFrameDataToArray Method  
========================================  

Copies the depth frame data to an unsigned array. <span id="syntaxSection"></span>

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
         UINT capacity,  
         UINT16 *frameData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
The size of the array.  

*frameData*    
Type: UINT16  
[out] The array to which to copy the depth frame data.  

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
TOCTitle : CopyFrameDataToArray Method
RLTitle : IDepthFrame::CopyFrameDataToArray Method
KeywordK : CopyFrameDataToArray method
KeywordK : IDepthFrame::CopyFrameDataToArray method
KeywordF : IDepthFrame::CopyFrameDataToArray
KeywordF : CopyFrameDataToArray
KeywordF : Microsoft.Kinect.kinect.IDepthFrame.CopyFrameDataToArray(UINT,UINT16@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrame.CopyFrameDataToArray(UINT,UINT16@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrame.CopyFrameDataToArray(UINT,UINT16@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrame::CopyFrameDataToArray
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
