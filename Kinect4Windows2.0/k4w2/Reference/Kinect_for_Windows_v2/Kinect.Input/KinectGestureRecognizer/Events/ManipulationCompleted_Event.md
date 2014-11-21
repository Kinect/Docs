KinectGestureRecognizer.ManipulationCompleted Event  
===================================================  

Occurs when the input points are lifted and all subsequent motion (translation or zoom) through inertia has ended.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a>&gt;^ ManipulationCompleted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectGestureRecognizer.md">KinectGestureRecognizer</a>, <a href="../../KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a>&gt; ManipulationCompleted</code></pre></td>
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
<td align="left"><pre><code>function onManipulationCompleted(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectGestureRecognizer.addEventListener(&quot;manipulationcompleted&quot;, onManipulationCompleted);  
kinectGestureRecognizer.removeEventListener(&quot;manipulationcompleted&quot;, onManipulationCompleted);  

- or -  

kinectGestureRecognizer.onmanipulationcompleted = onManipulationCompleted;</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

Inertia is the tendency of an object to resist any change in its state of rest or its velocity.  

This event is raised before inertia processing.  

Inertia behavior for this manipulation can be customized in the handler for this event. For example, inertia can be set to end after a specific distance or UI is displayed.  

| ![](../../../../../../resources/note.gif)Note        |
|------------------------------------------------------|
| These settings cannot be customized after the event. |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ECB"></span>

See also  
========  

<span id="ID4EEB"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ManipulationCompleted Event
RLTitle : KinectGestureRecognizer.ManipulationCompleted Event
KeywordK : ManipulationCompleted event
KeywordK : KinectGestureRecognizer.ManipulationCompleted event
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationCompleted
KeywordF : KinectGestureRecognizer.ManipulationCompleted
KeywordF : ManipulationCompleted
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationCompleted
KeywordA : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationCompleted
AssetID : E:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationCompleted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ManipulationCompleted
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
