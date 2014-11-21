IKinectGestureRecognizerManipulationHandler::OnManipulationCompleted Method  
===========================================================================  

Occurs when the input points are lifted and all subsequent motion (translation or zoom) through inertia has ended. <span id="syntaxSection"></span>

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
HRESULT OnManipulationCompleted(  
         IKinectManipulationCompletedEventArgs *args  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*args*    
Type: IKinectManipulationCompletedEventArgs  
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
TOCTitle : OnManipulationCompleted Method
RLTitle : IKinectGestureRecognizerManipulationHandler::OnManipulationCompleted Method
KeywordK : OnManipulationCompleted method
KeywordK : IKinectGestureRecognizerManipulationHandler::OnManipulationCompleted method
KeywordF : IKinectGestureRecognizerManipulationHandler::OnManipulationCompleted
KeywordF : OnManipulationCompleted
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationCompleted(IKinectManipulationCompletedEventArgs)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationCompleted(IKinectManipulationCompletedEventArgs)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationCompleted(IKinectManipulationCompletedEventArgs)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler::OnManipulationCompleted
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
