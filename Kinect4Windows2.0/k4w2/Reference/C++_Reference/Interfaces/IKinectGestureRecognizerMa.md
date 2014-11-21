IKinectGestureRecognizerManipulationHandler Interface  
=====================================================  

Provides methods for handling Kinect manipulation events. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IKinectGestureRecognizerManipulationHandler : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectGestureRecognizerManipulationHandler** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizerMa/Methods/OnManipulationCompleted.md">OnManipulationCompleted</a></td>
<td align="left">Occurs when the input points are lifted and all subsequent motion (translation or zoom) through inertia has ended.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizerMa/Methods/OnManipulationInertiaStart.md">OnManipulationInertiaStarting</a></td>
<td align="left">Called when all contact points are lifted during a manipulation and the velocity of the manipulation is significant enough to initiate inertia behavior (translation and zoom continue after the input pointers are lifted).</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizerMa/Methods/OnManipulationStarted_Method.md">OnManipulationStarted</a></td>
<td align="left">Called when one or more input points have been initiated and subsequent motion (translation or zoom) has begun.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizerMa/Methods/OnManipulationUpdated_Method.md">OnManipulationUpdated</a></td>
<td align="left">Called after one or more input points have been initiated and subsequent motion (translation or zoom) is under way.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IKinectGestureRecognizerManipulationHandler Interface
RLTitle : IKinectGestureRecognizerManipulationHandler Interface
KeywordK : IKinectGestureRecognizerManipulationHandler interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectGestureRecognizerManipulationHandler
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler
KeywordA : T:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler
AssetID : T:Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerManipulationHandler
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
