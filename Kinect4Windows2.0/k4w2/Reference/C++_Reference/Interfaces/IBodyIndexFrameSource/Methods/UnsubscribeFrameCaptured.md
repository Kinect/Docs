IBodyIndexFrameSource::UnsubscribeFrameCaptured Method  
======================================================  

Unsubscribes a subscribed event handler when a frame has been captured. <span id="syntaxSection"></span>

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
HRESULT UnsubscribeFrameCaptured(  
         WAITABLE_HANDLE waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle of the subscribed event handler.  

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
TOCTitle : UnsubscribeFrameCaptured Method
RLTitle : IBodyIndexFrameSource::UnsubscribeFrameCaptured Method
KeywordK : UnsubscribeFrameCaptured method
KeywordK : IBodyIndexFrameSource::UnsubscribeFrameCaptured method
KeywordF : IBodyIndexFrameSource::UnsubscribeFrameCaptured
KeywordF : UnsubscribeFrameCaptured
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameSource.UnsubscribeFrameCaptured(WAITABLE_HANDLE)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrameSource.UnsubscribeFrameCaptured(WAITABLE_HANDLE)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrameSource.UnsubscribeFrameCaptured(WAITABLE_HANDLE)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameSource::UnsubscribeFrameCaptured
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
