IKinectGestureRecognizerSelectionHandler::OnHolding Method  
==========================================================  

Called when a user performs a press and hold gesture. <span id="syntaxSection"></span>

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
HRESULT OnHolding(  
         IKinectHoldingEventArgs *args  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*args*    
Type: IKinectHoldingEventArgs  
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
TOCTitle : OnHolding Method
RLTitle : IKinectGestureRecognizerSelectionHandler::OnHolding Method
KeywordK : OnHolding method
KeywordK : IKinectGestureRecognizerSelectionHandler::OnHolding method
KeywordF : IKinectGestureRecognizerSelectionHandler::OnHolding
KeywordF : OnHolding
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnHolding(IKinectHoldingEventArgs)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnHolding(IKinectHoldingEventArgs)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler.OnHolding(IKinectHoldingEventArgs)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler::OnHolding
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
