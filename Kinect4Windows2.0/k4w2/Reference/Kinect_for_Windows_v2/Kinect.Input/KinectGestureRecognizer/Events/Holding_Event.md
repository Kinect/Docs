KinectGestureRecognizer.Holding Event  
=====================================  

Occurs when a user performs a press and hold gesture.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectHoldingEventArgs_Class.md">KinectHoldingEventArgs</a>&gt;^ Holding {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectHoldingEventArgs_Class.md">KinectHoldingEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectHoldingEventArgs_Class.md">KinectHoldingEventArgs</a>&gt; Holding</code></pre></td>
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
<td align="left"><pre><code>function onHolding(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;holding&quot;, onHolding);  
kinectGestureRecognizer.removeEventListener(&quot;holding&quot;, onHolding);  

- or -  

kinectGestureRecognizer.onholding = onHolding;</code></pre></td>
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
TOCTitle : Holding Event
RLTitle : KinectGestureRecognizer.Holding Event
KeywordK : Holding event
KeywordK : KinectGestureRecognizer.Holding event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.Holding
KeywordF : KinectGestureRecognizer.Holding
KeywordF : Holding
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.Holding
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.Holding
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.Holding
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.Holding
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
