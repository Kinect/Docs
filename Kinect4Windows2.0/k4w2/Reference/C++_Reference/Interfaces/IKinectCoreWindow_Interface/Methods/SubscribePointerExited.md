IKinectCoreWindow::SubscribePointerExited Method  
================================================  

Subscribes to the specified event handler to handle pointer exited events. <span id="syntaxSection"></span>

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
HRESULT SubscribePointerExited(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] The handle to the subscribed event handler.  

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
TOCTitle : SubscribePointerExited Method
RLTitle : IKinectCoreWindow::SubscribePointerExited Method
KeywordK : SubscribePointerExited method
KeywordK : IKinectCoreWindow::SubscribePointerExited method
KeywordF : IKinectCoreWindow::SubscribePointerExited
KeywordF : SubscribePointerExited
KeywordF : Microsoft.Kinect.kinect.IKinectCoreWindow.SubscribePointerExited(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectCoreWindow.SubscribePointerExited(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.kinect.IKinectCoreWindow.SubscribePointerExited(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectCoreWindow::SubscribePointerExited
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
