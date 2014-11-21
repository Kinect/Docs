KinectGestureRecognizer.ManipulationUpdated Event  
=================================================  

Occurs after one or more input points have been initiated and subsequent motion (translation or zoom) is under way.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a>&gt;^ ManipulationUpdated {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a>&gt; ManipulationUpdated</code></pre></td>
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
<td align="left"><pre><code>function onManipulationUpdated(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;manipulationupdated&quot;, onManipulationUpdated);  
kinectGestureRecognizer.removeEventListener(&quot;manipulationupdated&quot;, onManipulationUpdated);  

- or -  

kinectGestureRecognizer.onmanipulationupdated = onManipulationUpdated;</code></pre></td>
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
TOCTitle : ManipulationUpdated Event
RLTitle : KinectGestureRecognizer.ManipulationUpdated Event
KeywordK : ManipulationUpdated event
KeywordK : KinectGestureRecognizer.ManipulationUpdated event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationUpdated
KeywordF : KinectGestureRecognizer.ManipulationUpdated
KeywordF : ManipulationUpdated
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationUpdated
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationUpdated
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationUpdated
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationUpdated
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
