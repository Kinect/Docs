IKinectGestureRecognizerSelectionHandler::OnPressingCompleted Method  
====================================================================  

Called when the system no longer considers the pointer to be over a tappable gesture recognizer. <span id="syntaxSection"></span>

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
HRESULT OnPressingCompleted(  
         IKinectPressingCompletedEventArgs *args  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*args*    
Type: IKinectPressingCompletedEventArgs  
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
TOCTitle : OnPressingCompleted Method
RLTitle : IKinectGestureRecognizerSelectionHandler::OnPressingCompleted Method
KeywordK : OnPressingCompleted method
KeywordK : IKinectGestureRecognizerSelectionHandler::OnPressingCompleted method
KeywordF : IKinectGestureRecognizerSelectionHandler::OnPressingCompleted
KeywordF : OnPressingCompleted
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnPressingCompleted(IKinectPressingCompletedEventArgs)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnPressingCompleted(IKinectPressingCompletedEventArgs)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnPressingCompleted(IKinectPressingCompletedEventArgs)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler::OnPressingCompleted
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
