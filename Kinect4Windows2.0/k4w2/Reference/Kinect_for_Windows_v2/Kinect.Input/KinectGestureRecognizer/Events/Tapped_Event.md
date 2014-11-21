KinectGestureRecognizer.Tapped Event  
====================================  

Occurs when the Kinect for Windows sensor input is interpreted as a tap gesture.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a>&gt;^ Tapped {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a>&gt; Tapped</code></pre></td>
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
<td align="left"><pre><code>function onTapped(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;tapped&quot;, onTapped);  
kinectGestureRecognizer.removeEventListener(&quot;tapped&quot;, onTapped);  

- or -  

kinectGestureRecognizer.ontapped = onTapped;</code></pre></td>
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
TOCTitle : Tapped Event
RLTitle : KinectGestureRecognizer.Tapped Event
KeywordK : Tapped event
KeywordK : KinectGestureRecognizer.Tapped event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.Tapped
KeywordF : KinectGestureRecognizer.Tapped
KeywordF : Tapped
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.Tapped
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.Tapped
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.Tapped
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.Tapped
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
