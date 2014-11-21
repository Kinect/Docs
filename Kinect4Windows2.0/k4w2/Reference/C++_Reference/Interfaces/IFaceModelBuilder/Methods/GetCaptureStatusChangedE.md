IFaceModelBuilder::GetCaptureStatusChangedEventData Method  
==========================================================  

Gets data for the CaptureStatusChanged event. <span id="syntaxSection"></span>

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
HRESULT GetCaptureStatusChangedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ICaptureStatusChangedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to the event.  

*eventData*    
Type: ICaptureStatusChangedEventArgs  
[out] The event data.  

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
TOCTitle : GetCaptureStatusChangedEventData Method
RLTitle : IFaceModelBuilder::GetCaptureStatusChangedEventData Method
KeywordK : GetCaptureStatusChangedEventData method
KeywordK : IFaceModelBuilder::GetCaptureStatusChangedEventData method
KeywordF : IFaceModelBuilder::GetCaptureStatusChangedEventData
KeywordF : GetCaptureStatusChangedEventData
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.GetCaptureStatusChangedEventData(WAITABLE_HANDLE,ICaptureStatusChangedEventArgs@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCaptureStatusChangedEventData(WAITABLE_HANDLE,ICaptureStatusChangedEventArgs@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCaptureStatusChangedEventData(WAITABLE_HANDLE,ICaptureStatusChangedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::GetCaptureStatusChangedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
