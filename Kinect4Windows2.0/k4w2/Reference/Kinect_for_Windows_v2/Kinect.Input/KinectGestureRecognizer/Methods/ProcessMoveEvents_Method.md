KinectGestureRecognizer.ProcessMoveEvents Method  
================================================  

Processes pointer input and raises the [KinectGestureRecognizer](../../KinectGestureRecognizer.md) events appropriate to a pointer move action for the gestures and manipulations specified by the [GestureSettings](../Properties/GestureSettings_Property.md) property. <span id="syntaxSection"></span>

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
void ProcessMoveEvents(  
         IVector&lt;<a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>&gt;^ value  
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
<td align="left"><pre><code>public void ProcessMoveEvents (  
         IList&lt;<a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>&gt;value  
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
<td align="left"><pre><code>kinectGestureRecognizer.processMoveEvents(value);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EN"></span>
#### Parameters  

*value*    
[C++] Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[KinectPointerPoint](../../KinectPointerPoint_Class.md)\>
  [C\#] Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6.aspx)\<[KinectPointerPoint](../../KinectPointerPoint_Class.md)\>
  [JavaScript] Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[KinectPointerPoint](../../KinectPointerPoint_Class.md)\>
   

The pointer location history based on the [PointerId](../../KinectPointerPoint_Class/Properties/PointerId_Property.md). If no history is available then the value is the current location of the input pointer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EKB"></span>

See also  
========  

<span id="ID4EMB"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessMoveEvents Method
RLTitle : KinectGestureRecognizer.ProcessMoveEvents Method
KeywordK : ProcessMoveEvents method
KeywordK : KinectGestureRecognizer.ProcessMoveEvents method
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessMoveEvents
KeywordF : KinectGestureRecognizer.ProcessMoveEvents
KeywordF : ProcessMoveEvents
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessMoveEvents(Windows.Foundation.Collections.IVector{WindowsPreview.Kinect.Input.KinectPointerPoint})
KeywordA : M:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessMoveEvents(Windows.Foundation.Collections.IVector{WindowsPreview.Kinect.Input.KinectPointerPoint})
AssetID : M:WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessMoveEvents(Windows.Foundation.Collections.IVector{WindowsPreview.Kinect.Input.KinectPointerPoint})
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.ProcessMoveEvents
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
