KinectGestureRecognizer.PressingStarted Event  
=============================================  

Occurs when the pointer begins a press gesture over a tappable gesture recognizer.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingStartedEvent.md">KinectPressingStartedEventArgs</a>&gt;^ PressingStarted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingStartedEvent.md">KinectPressingStartedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingStartedEvent.md">KinectPressingStartedEventArgs</a>&gt; PressingStarted</code></pre></td>
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
<td align="left"><pre><code>function onPressingStarted(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;pressingstarted&quot;, onPressingStarted);  
kinectGestureRecognizer.removeEventListener(&quot;pressingstarted&quot;, onPressingStarted);  

- or -  

kinectGestureRecognizer.onpressingstarted = onPressingStarted;</code></pre></td>
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
TOCTitle : PressingStarted Event
RLTitle : KinectGestureRecognizer.PressingStarted Event
KeywordK : PressingStarted event
KeywordK : KinectGestureRecognizer.PressingStarted event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingStarted
KeywordF : KinectGestureRecognizer.PressingStarted
KeywordF : PressingStarted
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingStarted
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingStarted
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingStarted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingStarted
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
