KinectGestureRecognizer.ManipulationStarted Event  
=================================================  

Occurs when one or more input points have been initiated and subsequent motion (translation or zoom) has begun.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a>&gt;^ ManipulationStarted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a>&gt; ManipulationStarted</code></pre></td>
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
<td align="left"><pre><code>function onManipulationStarted(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;manipulationstarted&quot;, onManipulationStarted);  
kinectGestureRecognizer.removeEventListener(&quot;manipulationstarted&quot;, onManipulationStarted);  

- or -  

kinectGestureRecognizer.onmanipulationstarted = onManipulationStarted;</code></pre></td>
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
TOCTitle : ManipulationStarted Event
RLTitle : KinectGestureRecognizer.ManipulationStarted Event
KeywordK : ManipulationStarted event
KeywordK : KinectGestureRecognizer.ManipulationStarted event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationStarted
KeywordF : KinectGestureRecognizer.ManipulationStarted
KeywordF : ManipulationStarted
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationStarted
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationStarted
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationStarted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationStarted
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
