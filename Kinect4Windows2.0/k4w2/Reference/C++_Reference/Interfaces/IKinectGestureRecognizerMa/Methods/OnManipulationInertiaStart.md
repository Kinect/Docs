IKinectGestureRecognizerManipulationHandler::OnManipulationInertiaStarting Method  
=================================================================================  

Called when all contact points are lifted during a manipulation and the velocity of the manipulation is significant enough to initiate inertia behavior (translation and zoom continue after the input pointers are lifted). <span id="syntaxSection"></span>

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
HRESULT OnManipulationInertiaStarting(  
         IKinectManipulationInertiaStartingEventArgs *args  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*args*    
Type: IKinectManipulationInertiaStartingEventArgs  
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
TOCTitle : OnManipulationInertiaStarting Method
RLTitle : IKinectGestureRecognizerManipulationHandler::OnManipulationInertiaStarting Method
KeywordK : OnManipulationInertiaStarting method
KeywordK : IKinectGestureRecognizerManipulationHandler::OnManipulationInertiaStarting method
KeywordF : IKinectGestureRecognizerManipulationHandler::OnManipulationInertiaStarting
KeywordF : OnManipulationInertiaStarting
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationInertiaStarting(IKinectManipulationInertiaStartingEventArgs)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationInertiaStarting(IKinectManipulationInertiaStartingEventArgs)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler.OnManipulationInertiaStarting(IKinectManipulationInertiaStartingEventArgs)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler::OnManipulationInertiaStarting
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
