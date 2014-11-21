KinectManipulationUpdatedEventArgs.Cumulative Property  
======================================================  

Gets values that indicate the accumulated transformation deltas (translation, rotation, scale) for a manipulation from the beginning of the interaction to the [ManipulationUpdated](../../KinectGestureRecognizer/Events/ManipulationUpdated_Event.md) event. <span id="syntaxSection"></span>

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
property <a href="../../KinectManipulationDelta.md">KinectManipulationDelta</a> Cumulative {  
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
<td align="left"><pre><code>public <a href="../../KinectManipulationDelta.md">KinectManipulationDelta</a> Cumulative { get; }</code></pre></td>
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
<td align="left"><pre><code>var cumulative = kinectManipulationUpdatedEventArgs.cumulative;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EV"></span>
#### Property value  

Type: [KinectManipulationDelta](../../KinectManipulationDelta.md)  
 The accumulated transformation values up to the [ManipulationUpdated](../../KinectGestureRecognizer/Events/ManipulationUpdated_Event.md) event.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EEB"></span>

See also  
========  

<span id="ID4EGB"></span>
#### Reference  

[KinectManipulationUpdatedEventArgs Class](../../KinectManipulationUpdatedE.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Cumulative Property
RLTitle : KinectManipulationUpdatedEventArgs.Cumulative Property
KeywordK : Cumulative property
KeywordK : KinectManipulationUpdatedEventArgs.Cumulative property
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Cumulative
KeywordF : KinectManipulationUpdatedEventArgs.Cumulative
KeywordF : Cumulative
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Cumulative
KeywordA : P:WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Cumulative
AssetID : P:WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Cumulative
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Cumulative
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
