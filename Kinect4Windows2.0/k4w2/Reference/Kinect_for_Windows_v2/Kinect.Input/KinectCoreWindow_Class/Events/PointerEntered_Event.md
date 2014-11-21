KinectCoreWindow.PointerEntered Event  
=====================================  

Occurs when a pointer ID is first seen by the window.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt;^ PointerEntered {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt; PointerEntered</code></pre></td>
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
<td align="left"><pre><code>function onPointerEntered(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectCoreWindow.addEventListener(&quot;pointerentered&quot;, onPointerEntered);  
kinectCoreWindow.removeEventListener(&quot;pointerentered&quot;, onPointerEntered);  

- or -  

kinectCoreWindow.onpointerentered = onPointerEntered;</code></pre></td>
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

[KinectCoreWindow Class](../../KinectCoreWindow_Class.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PointerEntered Event
RLTitle : KinectCoreWindow.PointerEntered Event
KeywordK : PointerEntered event
KeywordK : KinectCoreWindow.PointerEntered event
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerEntered
KeywordF : KinectCoreWindow.PointerEntered
KeywordF : PointerEntered
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerEntered
KeywordA : E:WindowsPreview.Kinect.Input.KinectCoreWindow.PointerEntered
AssetID : E:WindowsPreview.Kinect.Input.KinectCoreWindow.PointerEntered
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerEntered
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
