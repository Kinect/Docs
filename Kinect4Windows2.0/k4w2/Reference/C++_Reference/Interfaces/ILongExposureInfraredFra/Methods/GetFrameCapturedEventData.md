ILongExposureInfraredFrameSource::GetFrameCapturedEventData Method  
==================================================================  

Gets the event data from the specified event handler when a new frame is captured. <span id="syntaxSection"></span>

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
HRESULT GetFrameCapturedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IFrameCapturedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to event handler that will process the event data.  

*eventData*    
Type: IFrameCapturedEventArgs  
[out] The event data.  

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
TOCTitle : GetFrameCapturedEventData Method
RLTitle : ILongExposureInfraredFrameSource::GetFrameCapturedEventData Method
KeywordK : GetFrameCapturedEventData method
KeywordK : ILongExposureInfraredFrameSource::GetFrameCapturedEventData method
KeywordF : ILongExposureInfraredFrameSource::GetFrameCapturedEventData
KeywordF : GetFrameCapturedEventData
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.GetFrameCapturedEventData(WAITABLE_HANDLE,IFrameCapturedEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.GetFrameCapturedEventData(WAITABLE_HANDLE,IFrameCapturedEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.GetFrameCapturedEventData(WAITABLE_HANDLE,IFrameCapturedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource::GetFrameCapturedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
