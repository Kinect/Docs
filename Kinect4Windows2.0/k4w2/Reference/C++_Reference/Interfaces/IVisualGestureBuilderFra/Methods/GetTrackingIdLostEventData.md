IVisualGestureBuilderFrameSource::GetTrackingIdLostEventData Method  
===================================================================  

Gets the event data from a tracking ID lost frame event. <span id="syntaxSection"></span>

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
HRESULT GetTrackingIdLostEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ITrackingIdLostEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to the event handler.  

*eventData*    
Type: ITrackingIdLostEventArgs  
[out] The event data.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetTrackingIdLostEventData Method
RLTitle : IVisualGestureBuilderFrameSource::GetTrackingIdLostEventData Method
KeywordK : GetTrackingIdLostEventData method
KeywordK : IVisualGestureBuilderFrameSource::GetTrackingIdLostEventData method
KeywordF : IVisualGestureBuilderFrameSource::GetTrackingIdLostEventData
KeywordF : GetTrackingIdLostEventData
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.GetTrackingIdLostEventData(WAITABLE_HANDLE,ITrackingIdLostEventArgs@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.GetTrackingIdLostEventData(WAITABLE_HANDLE,ITrackingIdLostEventArgs@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.GetTrackingIdLostEventData(WAITABLE_HANDLE,ITrackingIdLostEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource::GetTrackingIdLostEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
