IKinectGestureRecognizer::RegisterSelectionTappedHandler Method  
===============================================================  

Registers the handler for the selection tapped event. <span id="syntaxSection"></span>

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
HRESULT RegisterSelectionTappedHandler(  
         IKinectGestureRecognizerSelectionHandler *handler  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*handler*    
Type: IKinectGestureRecognizerSelectionHandler  
The event handler object.  

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
TOCTitle : RegisterSelectionTappedHandler Method
RLTitle : IKinectGestureRecognizer::RegisterSelectionTappedHandler Method
KeywordK : RegisterSelectionTappedHandler method
KeywordK : IKinectGestureRecognizer::RegisterSelectionTappedHandler method
KeywordF : IKinectGestureRecognizer::RegisterSelectionTappedHandler
KeywordF : RegisterSelectionTappedHandler
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.RegisterSelectionTappedHandler(IKinectGestureRecognizerSelectionHandler)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.RegisterSelectionTappedHandler(IKinectGestureRecognizerSelectionHandler)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.RegisterSelectionTappedHandler(IKinectGestureRecognizerSelectionHandler)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::RegisterSelectionTappedHandler
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
