IKinectGestureRecognizerSelectionHandler::OnPressingStarted Method  
==================================================================  

Called when the pointer begins a press gesture over a tappable gesture recognizer. <span id="syntaxSection"></span>

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
HRESULT OnPressingStarted(  
         IKinectPressingStartedEventArgs *args  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*args*    
Type: IKinectPressingStartedEventArgs  
The event data.  

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
TOCTitle : OnPressingStarted Method
RLTitle : IKinectGestureRecognizerSelectionHandler::OnPressingStarted Method
KeywordK : OnPressingStarted method
KeywordK : IKinectGestureRecognizerSelectionHandler::OnPressingStarted method
KeywordF : IKinectGestureRecognizerSelectionHandler::OnPressingStarted
KeywordF : OnPressingStarted
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnPressingStarted(IKinectPressingStartedEventArgs)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnPressingStarted(IKinectPressingStartedEventArgs)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnPressingStarted(IKinectPressingStartedEventArgs)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler::OnPressingStarted
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
