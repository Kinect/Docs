KinectCoreWindow.PointerMoved Event  
===================================  

Occurs when a pointer ID seen by the window moves.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt;^ PointerMoved {  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../KinectCoreWindow_Class.md">KinectCoreWindow</a>, <a href="../../KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a>&gt; PointerMoved</code></pre></td>
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
<td align="left"><pre><code>function onPointerMoved(eventArgs) { /* Your code */ }  

// addEventListener syntax  
kinectCoreWindow.addEventListener(&quot;pointermoved&quot;, onPointerMoved);  
kinectCoreWindow.removeEventListener(&quot;pointermoved&quot;, onPointerMoved);  

- or -  

kinectCoreWindow.onpointermoved = onPointerMoved;</code></pre></td>
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
TOCTitle : PointerMoved Event
RLTitle : KinectCoreWindow.PointerMoved Event
KeywordK : PointerMoved event
KeywordK : KinectCoreWindow.PointerMoved event
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerMoved
KeywordF : KinectCoreWindow.PointerMoved
KeywordF : PointerMoved
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerMoved
KeywordA : E:WindowsPreview.Kinect.Input.KinectCoreWindow.PointerMoved
AssetID : E:WindowsPreview.Kinect.Input.KinectCoreWindow.PointerMoved
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectCoreWindow.PointerMoved
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
