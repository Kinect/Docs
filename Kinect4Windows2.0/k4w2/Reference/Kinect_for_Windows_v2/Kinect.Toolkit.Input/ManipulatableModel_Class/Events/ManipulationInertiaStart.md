ManipulatableModel.ManipulationInertiaStarting Event  
====================================================  

Occurs when the user has completed a manipulation gesture associated with the Kinect Toolkit input element and the inertial phase of the gesture starts.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationInerti.md">KinectManipulationInertiaStartingEventArgs</a>&gt;^ ManipulationInertiaStarting {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationInerti.md">KinectManipulationInertiaStartingEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationInerti.md">KinectManipulationInertiaStartingEventArgs</a>&gt; ManipulationInertiaStarting</code></pre></td>
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
manipulatableModel.addEventListener(&quot;manipulationinertiastarting&quot;, onManipulationInertiaStarting);  
manipulatableModel.removeEventListener(&quot;manipulationinertiastarting&quot;, onManipulationInertiaStarting);  

- or -  

manipulatableModel.onmanipulationinertiastarting = onManipulationInertiaStarting;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[ManipulatableModel Class](../../ManipulatableModel_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ManipulationInertiaStarting Event
RLTitle : ManipulatableModel.ManipulationInertiaStarting Event
KeywordK : ManipulationInertiaStarting event
KeywordK : ManipulatableModel.ManipulationInertiaStarting event
KeywordF : Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationInertiaStarting
KeywordF : ManipulatableModel.ManipulationInertiaStarting
KeywordF : ManipulationInertiaStarting
KeywordF : Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationInertiaStarting
KeywordA : E:Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationInertiaStarting
AssetID : E:Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationInertiaStarting
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationInertiaStarting
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
