KinectCoreWindow.PointerExited Event  
====================================  

Occurs when a pointer moves outside the bounding box of the [KinectCoreWindow](../../KinectCoreWindow_Class.md). <span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt;^ PointerExited {  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt; PointerExited</code></pre></td>
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
<td align="left"><pre><code>function onPointerExited(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectCoreWindow.addEventListener(&quot;pointerexited&quot;, onPointerExited);  
kinectCoreWindow.removeEventListener(&quot;pointerexited&quot;, onPointerExited);  

- or -  

kinectCoreWindow.onpointerexited = onPointerExited;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E2"></span>

See also  
========  

<span id="ID4E4"></span>
#### Reference  

[KinectCoreWindow Class](../../KinectCoreWindow_Class.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PointerExited Event
RLTitle : KinectCoreWindow.PointerExited Event
KeywordK : PointerExited event
KeywordK : KinectCoreWindow.PointerExited event
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerExited
KeywordF : KinectCoreWindow.PointerExited
KeywordF : PointerExited
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerExited
KeywordA : E:WindowsPreview.Kinect.Input.KinectCoreWindow.PointerExited
AssetID : E:WindowsPreview.Kinect.Input.KinectCoreWindow.PointerExited
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerExited
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
