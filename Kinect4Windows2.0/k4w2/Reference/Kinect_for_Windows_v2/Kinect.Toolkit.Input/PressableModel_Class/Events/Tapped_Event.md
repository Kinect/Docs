PressableModel.Tapped Event  
===========================  

Occurs when the Kinect Toolkit input element is tapped. <span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a>&gt;^ Tapped {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IPressableModel_Interface.md">IPressableModel</a>, <a href="../../../Kinect.Input/KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a>&gt; Tapped</code></pre></td>
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
pressableModel.addEventListener(&quot;tapped&quot;, onTapped);  
pressableModel.removeEventListener(&quot;tapped&quot;, onTapped);  

- or -  

pressableModel.ontapped = onTapped;</code></pre></td>
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
TOCTitle : Tapped Event
RLTitle : PressableModel.Tapped Event
KeywordK : Tapped event
KeywordK : PressableModel.Tapped event
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.Tapped
KeywordF : PressableModel.Tapped
KeywordF : Tapped
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.Tapped
KeywordA : E:Microsoft.Kinect.Toolkit.Input.PressableModel.Tapped
AssetID : E:Microsoft.Kinect.Toolkit.Input.PressableModel.Tapped
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.PressableModel.Tapped
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
