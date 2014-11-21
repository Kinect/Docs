ILongExposureInfraredFrameSource::SubscribeFrameCaptured Method  
===============================================================  

Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped. <span id="syntaxSection"></span>

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
HRESULT SubscribeFrameCaptured(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] The handle to the event handler.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

Applications are only allowed to hold one frame locked at any given time. This event can be used to release the currently locked frame to allow the new one to be delivered to all subscribed readers. If the application does not free the old frame before a new frame arrives, the event will be raised again to notify that the frame has been dropped.  

The application should call the [GetFrameCapturedEventData](GetFrameCapturedEventData.md) method to retrieve the IFrameCapturedEventArgs. It should then look at the FrameStatus property to determine if a new frame has been queued, or if a frame has been dropped.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SubscribeFrameCaptured Method
RLTitle : ILongExposureInfraredFrameSource::SubscribeFrameCaptured Method
KeywordK : SubscribeFrameCaptured method
KeywordK : ILongExposureInfraredFrameSource::SubscribeFrameCaptured method
KeywordF : ILongExposureInfraredFrameSource::SubscribeFrameCaptured
KeywordF : SubscribeFrameCaptured
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.SubscribeFrameCaptured(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.SubscribeFrameCaptured(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.SubscribeFrameCaptured(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource::SubscribeFrameCaptured
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
