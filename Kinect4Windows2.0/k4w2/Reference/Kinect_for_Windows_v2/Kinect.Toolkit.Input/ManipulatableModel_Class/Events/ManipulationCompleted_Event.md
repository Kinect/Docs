ManipulatableModel.ManipulationCompleted Event  
==============================================  

Occurs when a manipulation gesture associated with the Kinect Toolkit input element completes.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a>&gt;^ ManipulationCompleted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a>&gt; ManipulationCompleted</code></pre></td>
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
manipulatableModel.addEventListener(&quot;manipulationcompleted&quot;, onManipulationCompleted);  
manipulatableModel.removeEventListener(&quot;manipulationcompleted&quot;, onManipulationCompleted);  

- or -  

manipulatableModel.onmanipulationcompleted = onManipulationCompleted;</code></pre></td>
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
TOCTitle : ManipulationCompleted Event
RLTitle : ManipulatableModel.ManipulationCompleted Event
KeywordK : ManipulationCompleted event
KeywordK : ManipulatableModel.ManipulationCompleted event
KeywordF : Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationCompleted
KeywordF : ManipulatableModel.ManipulationCompleted
KeywordF : ManipulationCompleted
KeywordF : Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationCompleted
KeywordA : E:Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationCompleted
AssetID : E:Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationCompleted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.ManipulatableModel.ManipulationCompleted
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
