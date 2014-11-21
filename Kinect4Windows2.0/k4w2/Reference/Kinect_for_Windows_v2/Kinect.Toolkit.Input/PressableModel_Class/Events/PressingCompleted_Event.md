PressableModel.PressingCompleted Event  
======================================  

Occurs when a press gesture associated with the Kinect Toolkit input element completes.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a>&gt;^ PressingCompleted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a>&gt; PressingCompleted</code></pre></td>
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
pressableModel.addEventListener(&quot;pressingcompleted&quot;, onPressingCompleted);  
pressableModel.removeEventListener(&quot;pressingcompleted&quot;, onPressingCompleted);  

- or -  

pressableModel.onpressingcompleted = onPressingCompleted;</code></pre></td>
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

[PressableModel Class](../../PressableModel_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PressingCompleted Event
RLTitle : PressableModel.PressingCompleted Event
KeywordK : PressingCompleted event
KeywordK : PressableModel.PressingCompleted event
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.PressingCompleted
KeywordF : PressableModel.PressingCompleted
KeywordF : PressingCompleted
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.PressingCompleted
KeywordA : E:Microsoft.Kinect.Toolkit.Input.PressableModel.PressingCompleted
AssetID : E:Microsoft.Kinect.Toolkit.Input.PressableModel.PressingCompleted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.PressableModel.PressingCompleted
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
