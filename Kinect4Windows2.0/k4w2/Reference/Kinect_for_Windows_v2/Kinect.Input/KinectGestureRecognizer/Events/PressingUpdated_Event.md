KinectGestureRecognizer.PressingUpdated Event  
=============================================  

Occurs as additional points are processed by the gesture recognizer during a press gesture.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a>&gt;^ PressingUpdated {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a>&gt; PressingUpdated</code></pre></td>
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
<td align="left"><pre><code>function onPressingUpdated(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;pressingupdated&quot;, onPressingUpdated);  
kinectGestureRecognizer.removeEventListener(&quot;pressingupdated&quot;, onPressingUpdated);  

- or -  

kinectGestureRecognizer.onpressingupdated = onPressingUpdated;</code></pre></td>
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
TOCTitle : PressingUpdated Event
RLTitle : KinectGestureRecognizer.PressingUpdated Event
KeywordK : PressingUpdated event
KeywordK : KinectGestureRecognizer.PressingUpdated event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingUpdated
KeywordF : KinectGestureRecognizer.PressingUpdated
KeywordF : PressingUpdated
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingUpdated
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingUpdated
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingUpdated
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingUpdated
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
