IKinectCoreWindow::GetPointerMovedEventData Method  
==================================================  

Gets the event data when a the pointer moved. <span id="syntaxSection"></span>

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
HRESULT GetPointerMovedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IKinectPointerEventArgs **eventData  
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
Type: IKinectPointerEventArgs  
[out] The event data.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetPointerMovedEventData Method
RLTitle : IKinectCoreWindow::GetPointerMovedEventData Method
KeywordK : GetPointerMovedEventData method
KeywordK : IKinectCoreWindow::GetPointerMovedEventData method
KeywordF : IKinectCoreWindow::GetPointerMovedEventData
KeywordF : GetPointerMovedEventData
KeywordF : Microsoft.Kinect.kinect.IKinectCoreWindow.GetPointerMovedEventData(WAITABLE_HANDLE,IKinectPointerEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectCoreWindow.GetPointerMovedEventData(WAITABLE_HANDLE,IKinectPointerEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.IKinectCoreWindow.GetPointerMovedEventData(WAITABLE_HANDLE,IKinectPointerEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectCoreWindow::GetPointerMovedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
