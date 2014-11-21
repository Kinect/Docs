KinectGestureRecognizer.ManipulationInertiaStarting Event  
=========================================================  

Occurs when all contact points are lifted during a manipulation and the velocity of the manipulation is significant enough to initiate inertia behavior (translation and zoom continue after the input pointers are lifted).<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationInerti.md">KinectManipulationInertiaStartingEventArgs</a>&gt;^ ManipulationInertiaStarting {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationInerti.md">KinectManipulationInertiaStartingEventArgs</a>&gt;^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationInerti.md">KinectManipulationInertiaStartingEventArgs</a>&gt; ManipulationInertiaStarting</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>function onManipulationInertiaStarting(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;manipulationinertiastarting&quot;, onManipulationInertiaStarting);  
kinectGestureRecognizer.removeEventListener(&quot;manipulationinertiastarting&quot;, onManipulationInertiaStarting);  

- or -  

kinectGestureRecognizer.onmanipulationinertiastarting = onManipulationInertiaStarting;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ManipulationInertiaStarting Event
RLTitle : KinectGestureRecognizer.ManipulationInertiaStarting Event
KeywordK : ManipulationInertiaStarting event
KeywordK : KinectGestureRecognizer.ManipulationInertiaStarting event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationInertiaStarting
KeywordF : KinectGestureRecognizer.ManipulationInertiaStarting
KeywordF : ManipulationInertiaStarting
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationInertiaStarting
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationInertiaStarting
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationInertiaStarting
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationInertiaStarting
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
