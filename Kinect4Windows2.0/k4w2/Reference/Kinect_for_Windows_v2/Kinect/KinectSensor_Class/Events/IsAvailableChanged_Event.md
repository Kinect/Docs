KinectSensor.IsAvailableChanged Event  
=====================================  

This event fires when the IsAvailable property changes. <span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectSensor_Class.md">KinectSensor</a>, <a href="../../IsAvailableChangedEventArgs.md">IsAvailableChangedEventArgs</a>&gt;^ IsAvailableChanged {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectSensor_Class.md">KinectSensor</a>, <a href="../../IsAvailableChangedEventArgs.md">IsAvailableChangedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectSensor_Class.md">KinectSensor</a>, <a href="../../IsAvailableChangedEventArgs.md">IsAvailableChangedEventArgs</a>&gt; IsAvailableChanged</code></pre></td>
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
<td align="left"><pre><code>function onIsAvailableChanged(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectSensor.addEventListener(&quot;isavailablechanged&quot;, onIsAvailableChanged);  
kinectSensor.removeEventListener(&quot;isavailablechanged&quot;, onIsAvailableChanged);  

- or -  

kinectSensor.onisavailablechanged = onIsAvailableChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[KinectSensor Class](../../KinectSensor_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IsAvailableChanged Event
RLTitle : KinectSensor.IsAvailableChanged Event
KeywordK : IsAvailableChanged event
KeywordK : KinectSensor.IsAvailableChanged event
KeywordF : WindowsPreview.Kinect.KinectSensor.IsAvailableChanged
KeywordF : KinectSensor.IsAvailableChanged
KeywordF : IsAvailableChanged
KeywordF : WindowsPreview.Kinect.KinectSensor.IsAvailableChanged
KeywordA : E:WindowsPreview.Kinect.KinectSensor.IsAvailableChanged
AssetID : E:WindowsPreview.Kinect.KinectSensor.IsAvailableChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectSensor.IsAvailableChanged
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
