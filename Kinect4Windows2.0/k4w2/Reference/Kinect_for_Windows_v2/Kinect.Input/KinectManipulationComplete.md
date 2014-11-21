KinectManipulationCompletedEventArgs Class  
==========================================  

Provides data for the [ManipulationCompleted](KinectGestureRecognizer/Events/ManipulationCompleted_Event.md) event. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class KinectManipulationCompletedEventArgs sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class KinectManipulationCompletedEventArgs</code></pre></td>
</tr>
</tbody>
</table>

| JavaScript                                                                             |
|----------------------------------------------------------------------------------------|
| /\* In JavaScript, properties of event data objects begin with a lowercase letter. \*/ |

<span id="classMembersSection"></span>

Members  
=======  

**KinectManipulationCompletedEventArgs** has the following members.  

<span id="publicpropertiesSection"></span>

Properties  
==========  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="KinectManipulationComplete/Properties/Cumulative_Property.md">Cumulative</a></td>
<td align="left">Gets values that indicate the accumulated transformation deltas (translation, rotation, scale) of a completed manipulation (from the start of the manipulation to the end of inertia).</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectManipulationComplete/Properties/PointerDeviceType_Property.md">PointerDeviceType</a></td>
<td align="left">Gets the device type of the input source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectManipulationComplete/Properties/Position_Property.md">Position</a></td>
<td align="left">Gets the location of the pointer associated with the manipulation for the last manipulation event.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectManipulationComplete/Properties/Velocities_Property.md">Velocities</a></td>
<td align="left">Gets values that indicate the velocities of the transformation deltas (translation, rotation, scale) for a manipulation at the <a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> event.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[WindowsPreview.Kinect.Input Namespace](../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectManipulationCompletedEventArgs Class
RLTitle : KinectManipulationCompletedEventArgs Class
KeywordK : KinectManipulationCompletedEventArgs class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs
KeywordF : KinectManipulationCompletedEventArgs
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs
KeywordA : T:WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs
AssetID : T:WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectManipulationCompletedEventArgs
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
