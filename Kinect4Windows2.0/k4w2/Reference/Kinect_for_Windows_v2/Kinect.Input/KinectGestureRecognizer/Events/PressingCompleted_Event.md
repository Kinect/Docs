KinectGestureRecognizer.PressingCompleted Event  
===============================================  

Occurs when the system no longer considers the pointer to be over a tappable gesture recognizer.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a>&gt;^ PressingCompleted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a>&gt; PressingCompleted</code></pre></td>
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
<td align="left"><pre><code>function onPressingCompleted(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;pressingcompleted&quot;, onPressingCompleted);  
kinectGestureRecognizer.removeEventListener(&quot;pressingcompleted&quot;, onPressingCompleted);  

- or -  

kinectGestureRecognizer.onpressingcompleted = onPressingCompleted;</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The conditions that raise this event are not determined by simple hit testing. If the pointer leaves the tappable gesture recognizer, the system still considers that gesture recognizer the target of the press gesture until the pointer moves far enough away or targets a different tappable gesture recognizer, whichever comes first.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EY"></span>

See also  
========  

<span id="ID4E1"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PressingCompleted Event
RLTitle : KinectGestureRecognizer.PressingCompleted Event
KeywordK : PressingCompleted event
KeywordK : KinectGestureRecognizer.PressingCompleted event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingCompleted
KeywordF : KinectGestureRecognizer.PressingCompleted
KeywordF : PressingCompleted
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingCompleted
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingCompleted
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingCompleted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.PressingCompleted
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
