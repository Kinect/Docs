PressableModel.Attach Method  
============================  

Attaches the Kinect Toolkit input element to the the specified [KinectGestureRecognizer Class](../../../Kinect.Input/KinectGestureRecognizer.md). <span id="syntaxSection"></span>

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
void Attach(  
         <a href="../../../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer</a>^ gestureRecognizer,  
         <a href="../../../Kinect.Input/KinectGestureSettings.md">KinectGestureSettings</a> PressableModelGestureSettings  
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
<td align="left"><pre><code>public void Attach (  
         <a href="../../../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer</a>gestureRecognizer,  
         <a href="../../../Kinect.Input/KinectGestureSettings.md">KinectGestureSettings</a> PressableModelGestureSettings  
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
<td align="left"><pre><code>pressableModel.attach(gestureRecognizer, PressableModelGestureSettings);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*gestureRecognizer*    
Type: [KinectGestureRecognizer](../../../Kinect.Input/KinectGestureRecognizer.md)  
 The [KinectGestureRecognizer Class](../../../Kinect.Input/KinectGestureRecognizer.md) from which the input element should be detached.  

*PressableModelGestureSettings*    
Type: [KinectGestureSettings](../../../Kinect.Input/KinectGestureSettings.md)  
The settings to be used by the gesture recognizer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EKB"></span>

See also  
========  

<span id="ID4EMB"></span>
#### Reference  

[PressableModel Class](../../PressableModel_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Attach Method
RLTitle : PressableModel.Attach Method
KeywordK : Attach method
KeywordK : PressableModel.Attach method
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.Attach
KeywordF : PressableModel.Attach
KeywordF : Attach
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.Attach(WindowsPreview.Kinect.Input.KinectGestureRecognizer,WindowsPreview.Kinect.Input.KinectGestureSettings)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.PressableModel.Attach(WindowsPreview.Kinect.Input.KinectGestureRecognizer,WindowsPreview.Kinect.Input.KinectGestureSettings)
AssetID : M:Microsoft.Kinect.Toolkit.Input.PressableModel.Attach(WindowsPreview.Kinect.Input.KinectGestureRecognizer,WindowsPreview.Kinect.Input.KinectGestureSettings)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.PressableModel.Attach
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
