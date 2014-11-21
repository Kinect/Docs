KinectGestureSettings Enumeration  
=================================  

Specifies the interactions that are supported by an Kinect for Windows application. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>[FlagsAttribute]  
public enum class KinectGestureSettings</code></pre></td>
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum KinectGestureSettings</code></pre></td>
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
<td align="left"><pre><code>var kinectGestureSettings = WindowsPreview.Kinect.Input.KinectGestureSettings.kinectHold;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ERE"></span>

Members  
=======  

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Member</th>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><strong>KinectHold</strong></td>
<td align="left">65536</td>
<td align="left"><p>Enable support for the press and hold gesture through Kinect gestures. The <a href="KinectGestureRecognizer/Events/Holding_Event.md">Holding</a> event is raised if a time threshold is crossed before the user moves the hand cursor away from the UI element.</p>
<p>This gesture can be used to display a context menu.</p></td>
</tr>
<tr class="even">
<td align="left"><strong>ManipulationScale</strong></td>
<td align="left">2048</td>
<td align="left">Enable support for the pinch or stretch gesture through pointer input.  
<p>These gestures can be used for optical or semantic zoom and resizing an object. The <a href="KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a>, <a href="KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a>, and <a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> events are all raised during the course of this interaction.</p></td>
</tr>
<tr class="odd">
<td align="left"><strong>ManipulationTranslateInertia</strong></td>
<td align="left">4096</td>
<td align="left">Enable support for scaling inertia after the pinch or stretch gesture (through pointer input) is complete. The <a href="KinectGestureRecognizer/Events/ManipulationInertiaStarting.md">ManipulationInertiaStarting</a> event is raised if inertia is enabled.</td>
</tr>
<tr class="even">
<td align="left"><strong>ManipulationTranslateRailsX</strong></td>
<td align="left">256</td>
<td align="left">Enable support for the <a href="http://msdn.microsoft.com/en-us/library/hh465299.aspx">slide</a> gesture through pointer input, on the horizontal axis using rails (guides). The <a href="KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a>, <a href="KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a>, and <a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> events are all raised during the course of this interaction.  
<p>This gesture can be used for rearranging objects.</p></td>
</tr>
<tr class="odd">
<td align="left"><strong>ManipulationTranslateRailsY</strong></td>
<td align="left">512</td>
<td align="left">Enable support for the <a href="http://msdn.microsoft.com/en-us/library/hh465299.aspx">slide</a> gesture through pointer input, on the vertical axis using rails (guides). The <a href="KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a>, <a href="KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a>, and <a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> events are all raised during the course of this interaction.  
<p>This gesture can be used for rearranging objects.</p></td>
</tr>
<tr class="even">
<td align="left"><strong>ManipulationTranslateX</strong></td>
<td align="left">64</td>
<td align="left">Enable support for the <a href="http://msdn.microsoft.com/en-us/library/hh465299.aspx">slide</a> gesture through pointer input, on the horizontal axis. The <a href="KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a>, <a href="KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a>, and <a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> events are all raised during the course of this interaction.  
<p>This gesture can be used for rearranging objects.</p></td>
</tr>
<tr class="odd">
<td align="left"><strong>ManipulationTranslateY</strong></td>
<td align="left">128</td>
<td align="left">Enable support for the <a href="http://msdn.microsoft.com/en-us/library/hh465299.aspx">slide</a> gesture through pointer input, on the vertical axis. The <a href="KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a>, <a href="KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a>, and <a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> events are all raised during the course of this interaction.  
<p>This gesture can be used for rearranging objects.</p></td>
</tr>
<tr class="even">
<td align="left"><strong>None</strong></td>
<td align="left">0</td>
<td align="left">Disable support for gestures and manipulations.</td>
</tr>
<tr class="odd">
<td align="left"><strong>Tap</strong></td>
<td align="left">1</td>
<td align="left">Enable support for the tap gesture.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EYE"></span>

See also  
========  

<span id="ID4E1E"></span>
#### Reference  

[WindowsPreview.Kinect.Input Namespace](../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectGestureSettings Enumeration
RLTitle : KinectGestureSettings Enumeration
KeywordK : KinectGestureSettings enumeration
KeywordK : WindowsPreview.Kinect.Input.KinectGestureSettings enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.Input.KinectGestureSettings
KeywordF : KinectGestureSettings
KeywordF : WindowsPreview.Kinect.Input.KinectGestureSettings
KeywordA : T:WindowsPreview.Kinect.Input.KinectGestureSettings
AssetID : T:WindowsPreview.Kinect.Input.KinectGestureSettings
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureSettings
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
