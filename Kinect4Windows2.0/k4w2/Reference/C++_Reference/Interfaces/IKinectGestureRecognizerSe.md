IKinectGestureRecognizerSelectionHandler Interface  
==================================================  

Provides methods for handling Kinect selection gesture events. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IKinectGestureRecognizerSelectionHandler : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectGestureRecognizerSelectionHandler** has the following members.  

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
<td align="left"><a href="IKinectGestureRecognizerSe/Methods/OnHolding_Method.md">OnHolding</a></td>
<td align="left">Called when a user performs a press and hold gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizerSe/Methods/OnPressingCompleted_Method.md">OnPressingCompleted</a></td>
<td align="left">Called when the system no longer considers the pointer to be over a tappable gesture recognizer.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizerSe/Methods/OnPressingStarted_Method.md">OnPressingStarted</a></td>
<td align="left">Called when the pointer begins a press gesture over a tappable gesture recognizer.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectGestureRecognizerSe/Methods/OnPressingUpdated_Method.md">OnPressingUpdated</a></td>
<td align="left">Called as additional points are processed by the gesture recognizer during a press gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectGestureRecognizerSe/Methods/OnTapped_Method.md">OnTapped</a></td>
<td align="left">Called when the Kinect for Windows sensor input is interpreted as a tap gesture.</td>
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
TOCTitle : IKinectGestureRecognizerSelectionHandler Interface
RLTitle : IKinectGestureRecognizerSelectionHandler Interface
KeywordK : IKinectGestureRecognizerSelectionHandler interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectGestureRecognizerSelectionHandler
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler
KeywordA : T:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler
AssetID : T:Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizerSelectionHandler
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
