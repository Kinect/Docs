IFaceModelBuilder::UnsubscribeCaptureStatusChanged Method  
=========================================================  

Unsubscribes an event handler from the CaptureStatusChanged event. <span id="syntaxSection"></span>

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
HRESULT UnsubscribeCaptureStatusChanged(  
         WAITABLE_HANDLE waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] Handle of the event handler.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : UnsubscribeCaptureStatusChanged Method
RLTitle : IFaceModelBuilder::UnsubscribeCaptureStatusChanged Method
KeywordK : UnsubscribeCaptureStatusChanged method
KeywordK : IFaceModelBuilder::UnsubscribeCaptureStatusChanged method
KeywordF : IFaceModelBuilder::UnsubscribeCaptureStatusChanged
KeywordF : UnsubscribeCaptureStatusChanged
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.UnsubscribeCaptureStatusChanged(WAITABLE_HANDLE)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.UnsubscribeCaptureStatusChanged(WAITABLE_HANDLE)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.UnsubscribeCaptureStatusChanged(WAITABLE_HANDLE)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::UnsubscribeCaptureStatusChanged
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
