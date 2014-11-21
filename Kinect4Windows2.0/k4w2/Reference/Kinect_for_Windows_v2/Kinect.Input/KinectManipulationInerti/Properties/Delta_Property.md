KinectManipulationInertiaStartingEventArgs.Delta Property  
=========================================================  

Gets values that indicate the changes in the transformation deltas (translation, rotation, scale) of a manipulation since the last manipulation event. <span id="syntaxSection"></span>

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
property <a href="../../KinectManipulationDelta.md">KinectManipulationDelta</a> Delta {  
         <a href="../../KinectManipulationDelta.md">KinectManipulationDelta</a> get ();  
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
<td align="left"><pre><code>public <a href="../../KinectManipulationDelta.md">KinectManipulationDelta</a> Delta { get; }</code></pre></td>
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
<td align="left"><pre><code>var delta = kinectManipulationInertiaStartingEventArgs.delta;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

Type: [KinectManipulationDelta](../../KinectManipulationDelta.md)  
The changes in transformation values since the last event.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[KinectManipulationInertiaStartingEventArgs Class](../../KinectManipulationInerti.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Delta Property
RLTitle : KinectManipulationInertiaStartingEventArgs.Delta Property
KeywordK : Delta property
KeywordK : KinectManipulationInertiaStartingEventArgs.Delta property
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationInertiaStartingEventArgs.Delta
KeywordF : KinectManipulationInertiaStartingEventArgs.Delta
KeywordF : Delta
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationInertiaStartingEventArgs.Delta
KeywordA : P:WindowsPreview.Kinect.Input.KinectManipulationInertiaStartingEventArgs.Delta
AssetID : P:WindowsPreview.Kinect.Input.KinectManipulationInertiaStartingEventArgs.Delta
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectManipulationInertiaStartingEventArgs.Delta
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
