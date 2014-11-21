KinectManipulationCompletedEventArgs.Velocities Property  
========================================================  

Gets values that indicate the velocities of the transformation deltas (translation, rotation, scale) for a manipulation at the [ManipulationCompleted](../../KinectGestureRecognizer/Events/ManipulationCompleted.md) event. <span id="syntaxSection"></span>

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
property <a href="../../KinectManipulationVeloci.md">KinectManipulationVelocities</a> Velocities {  
         <a href="../../KinectManipulationVeloci.md">KinectManipulationVelocities</a> get ();  
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
<td align="left"><pre><code>public <a href="../../KinectManipulationVeloci.md">KinectManipulationVelocities</a> Velocities { get; }</code></pre></td>
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
<td align="left"><pre><code>var velocities = kinectManipulationCompletedEventArgs.velocities;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EV"></span>
#### Property value  

Type: [KinectManipulationVelocities](../../KinectManipulationVeloci.md)  
 The velocities of the accumulated transformations since a [ManipulationStarted](../../KinectGestureRecognizer/Events/ManipulationStarted_Event.md) event.  

<span id="remarks"></span>

Remarks  
=======  

Velocity is the distance an object travels in a specified direction during a unit of time.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EJB"></span>

See also  
========  

<span id="ID4ELB"></span>
#### Reference  

[KinectManipulationCompletedEventArgs Class](../../KinectManipulationComple.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Velocities Property
RLTitle : KinectManipulationCompletedEventArgs.Velocities Property
KeywordK : Velocities property
KeywordK : KinectManipulationCompletedEventArgs.Velocities property
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs.Velocities
KeywordF : KinectManipulationCompletedEventArgs.Velocities
KeywordF : Velocities
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs.Velocities
KeywordA : P:WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs.Velocities
AssetID : P:WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs.Velocities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs.Velocities
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
