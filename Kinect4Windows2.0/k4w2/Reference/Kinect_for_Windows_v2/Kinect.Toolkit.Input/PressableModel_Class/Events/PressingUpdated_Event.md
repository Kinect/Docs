PressableModel.PressingUpdated Event  
====================================  

Occurs when a press gesture associated with the Kinect Toolkit input element is updated.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a>&gt;^ PressingUpdated {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a>&gt; PressingUpdated</code></pre></td>
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
pressableModel.addEventListener(&quot;pressingupdated&quot;, onPressingUpdated);  
pressableModel.removeEventListener(&quot;pressingupdated&quot;, onPressingUpdated);  

- or -  

pressableModel.onpressingupdated = onPressingUpdated;</code></pre></td>
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
TOCTitle : PressingUpdated Event
RLTitle : PressableModel.PressingUpdated Event
KeywordK : PressingUpdated event
KeywordK : PressableModel.PressingUpdated event
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.PressingUpdated
KeywordF : PressableModel.PressingUpdated
KeywordF : PressingUpdated
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.PressingUpdated
KeywordA : E:Microsoft.Kinect.Toolkit.Input.PressableModel.PressingUpdated
AssetID : E:Microsoft.Kinect.Toolkit.Input.PressableModel.PressingUpdated
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.PressableModel.PressingUpdated
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
