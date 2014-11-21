MultiSourceFrameReader.MultiSourceFrameArrived Event  
====================================================  

Event that fires whenever a frame is captured.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>, <a href="../../MultiSourceFrameArrivedEve.md">MultiSourceFrameArrivedEventArgs</a>&gt;^ MultiSourceFrameArrived {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>, <a href="../../MultiSourceFrameArrivedEve.md">MultiSourceFrameArrivedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>, <a href="../../MultiSourceFrameArrivedEve.md">MultiSourceFrameArrivedEventArgs</a>&gt; MultiSourceFrameArrived</code></pre></td>
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
<td align="left"><pre><code>function onMultiSourceFrameArrived(eventArgs) { /* Your code */ }  

// addEventListener syntax  
multiSourceFrameReader.addEventListener(&quot;multisourceframearrived&quot;, onMultiSourceFrameArrived);  
multiSourceFrameReader.removeEventListener(&quot;multisourceframearrived&quot;, onMultiSourceFrameArrived);  

- or -  

multiSourceFrameReader.onmultisourceframearrived = onMultiSourceFrameArrived;</code></pre></td>
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

[MultiSourceFrameReader Class](../../MultiSourceFrameReader_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MultiSourceFrameArrived Event
RLTitle : MultiSourceFrameReader.MultiSourceFrameArrived Event
KeywordK : MultiSourceFrameArrived event
KeywordK : MultiSourceFrameReader.MultiSourceFrameArrived event
KeywordF : WindowsPreview.Kinect.MultiSourceFrameReader.MultiSourceFrameArrived
KeywordF : MultiSourceFrameReader.MultiSourceFrameArrived
KeywordF : MultiSourceFrameArrived
KeywordF : WindowsPreview.Kinect.MultiSourceFrameReader.MultiSourceFrameArrived
KeywordA : E:WindowsPreview.Kinect.MultiSourceFrameReader.MultiSourceFrameArrived
AssetID : E:WindowsPreview.Kinect.MultiSourceFrameReader.MultiSourceFrameArrived
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.MultiSourceFrameReader.MultiSourceFrameArrived
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
