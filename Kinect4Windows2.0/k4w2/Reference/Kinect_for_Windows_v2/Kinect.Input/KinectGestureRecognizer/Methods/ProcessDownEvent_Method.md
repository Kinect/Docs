KinectGestureRecognizer.ProcessDownEvent Method  
===============================================  

Processes pointer input and raises the [KinectGestureRecognizer](../../KinectGestureRecognizer.md) events appropriate to a pointer down action for the gestures and manipulations specified by the [GestureSettings](../Properties/GestureSettings_Property.md) property. <span id="syntaxSection"></span>

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
void ProcessDownEvent(  
         <a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>^ value  
)</code></pre></td>
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
<td align="left"><pre><code>public void ProcessDownEvent (  
         <a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>value  
)</code></pre></td>
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
<td align="left"><pre><code>kinectGestureRecognizer.processDownEvent(value);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EN"></span>
#### Parameters  

*value*    
Type: [KinectPointerPoint](../../KinectPointerPoint_Class.md)  
The input point.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EDB"></span>

See also  
========  

<span id="ID4EFB"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessDownEvent Method
RLTitle : KinectGestureRecognizer.ProcessDownEvent Method
KeywordK : ProcessDownEvent method
KeywordK : KinectGestureRecognizer.ProcessDownEvent method
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessDownEvent
KeywordF : KinectGestureRecognizer.ProcessDownEvent
KeywordF : ProcessDownEvent
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessDownEvent(WindowsPreview.Kinect.Input.KinectPointerPoint)
KeywordA : M:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessDownEvent(WindowsPreview.Kinect.Input.KinectPointerPoint)
AssetID : M:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessDownEvent(WindowsPreview.Kinect.Input.KinectPointerPoint)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessDownEvent
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
