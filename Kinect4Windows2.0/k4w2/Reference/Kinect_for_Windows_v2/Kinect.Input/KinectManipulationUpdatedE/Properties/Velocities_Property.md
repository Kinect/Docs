KinectManipulationUpdatedEventArgs.Velocities Property  
======================================================  

Gets values that indicate the velocities of the transformation deltas (translation, rotation, scale) for a manipulation at the [ManipulationUpdated](../../KinectGestureRecognizer/Events/ManipulationUpdated_Event.md) event. <span id="syntaxSection"></span>

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
property <a href="../../KinectManipulationVelocities.md">KinectManipulationVelocities</a> Velocities {  
         <a href="../../KinectManipulationVelocities.md">KinectManipulationVelocities</a> get ();  
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
<td align="left"><pre><code>public <a href="../../KinectManipulationVelocities.md">KinectManipulationVelocities</a> Velocities { get; }</code></pre></td>
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
<td align="left"><pre><code>var velocities = kinectManipulationUpdatedEventArgs.velocities;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EV"></span>
#### Property value  

Type: [KinectManipulationVelocities](../../KinectManipulationVelocities.md)  
 The velocities of the accumulated transformations since a [ManipulationUpdated](../../KinectGestureRecognizer/Events/ManipulationUpdated_Event.md) event.  

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
TOCTitle : Velocities Property
RLTitle : KinectManipulationUpdatedEventArgs.Velocities Property
KeywordK : Velocities property
KeywordK : KinectManipulationUpdatedEventArgs.Velocities property
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Velocities
KeywordF : KinectManipulationUpdatedEventArgs.Velocities
KeywordF : Velocities
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Velocities
KeywordA : P:WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Velocities
AssetID : P:WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Velocities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectManipulationUpdatedEventArgs.Velocities
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
