KinectGestureRecognizer Class  
=============================  

Provides gesture and manipulation recognition, and settings. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class KinectGestureRecognizer sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class KinectGestureRecognizer</code></pre></td>
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
<td align="left"><pre><code>var kinectGestureRecognizer = WindowsPreview.Kinect.Input.KinectGestureRecognizer;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**KinectGestureRecognizer** has the following members.  

<span id="publicconstructorsSection"></span>

Constructors  
============  

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
<td align="left"><a href="KinectGestureRecognizer/KinectGestureRecognizer.md">KinectGestureRecognizer</a></td>
<td align="left">Initializes a new instance of the <a href="">KinectGestureRecognizer</a> class.</td>
</tr>
</tbody>
</table>

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
<td align="left"><a href="KinectGestureRecognizer/Properties/AutoProcessInertia_Property.md">AutoProcessInertia</a></td>
<td align="left">Gets or sets a value that indicates whether manipulations during inertia are generated automatically. If false, the app is expected to call ProcessInertia periodically.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Properties/BoundingRect_Property.md">BoundingRect</a></td>
<td align="left">Gets the bounds of a tappable gesture recognizer.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Properties/GestureSettings_Property.md">GestureSettings</a></td>
<td align="left">Gets or sets a value that indicates the gesture and manipulation settings supported by an application.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Properties/InertiaTranslationDecelera.md">InertiaTranslationDeceleration</a></td>
<td align="left">Gets or sets a value that indicates the rate of deceleration from the start of inertia to the end of inertia (when the translation manipulation is complete).</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Properties/InertiaTranslationDisplace.md">InertiaTranslationDisplacement</a></td>
<td align="left">Gets or sets a value that indicates the relative change in the screen location of an object from the start of inertia to the end of inertia (when the translation manipulation is complete).</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets a value that indicates whether an interaction is being processed.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Properties/IsInertial_Property.md">IsInertial</a></td>
<td align="left">Gets a value that indicates whether a manipulation is still being processed during inertia (no input points are active).</td>
</tr>
</tbody>
</table>

<span id="publicmethodsSection"></span>

Methods  
=======  

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
<td align="left"><a href="KinectGestureRecognizer/Methods/CompleteGesture_Method.md">CompleteGesture</a></td>
<td align="left">Causes the gesture recognizer to finalize an interaction.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Methods/ProcessDownEvent_Method.md">ProcessDownEvent</a></td>
<td align="left">Processes pointer input and raises the <a href="">KinectGestureRecognizer</a> events appropriate to a pointer down action for the gestures and manipulations specified by the <a href="KinectGestureRecognizer/Properties/GestureSettings_Property.md">GestureSettings</a> property.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Methods/ProcessInertia_Method.md">ProcessInertia</a></td>
<td align="left">Performs inertia calculations and raises the various inertia events.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Methods/ProcessMoveEvents_Method.md">ProcessMoveEvents</a></td>
<td align="left">Processes pointer input and raises the <a href="">KinectGestureRecognizer</a> events appropriate to a pointer move action for the gestures and manipulations specified by the <a href="KinectGestureRecognizer/Properties/GestureSettings_Property.md">GestureSettings</a> property.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Methods/ProcessUpEvent_Method.md">ProcessUpEvent</a></td>
<td align="left">Processes pointer input and raises the <a href="">KinectGestureRecognizer</a> events appropriate to a pointer up action for the gestures and manipulations specified by the <a href="KinectGestureRecognizer/Properties/GestureSettings_Property.md">GestureSettings</a> property.&quot;</td>
</tr>
</tbody>
</table>

<span id="publiceventsSection"></span>

Events  
======  

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
<td align="left"><a href="KinectGestureRecognizer/Events/Holding_Event.md">Holding</a></td>
<td align="left">Occurs when a user performs a press and hold gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a></td>
<td align="left">Occurs when the input points are lifted and all subsequent motion (translation or zoom) through inertia has ended.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Events/ManipulationInertiaStarting.md">ManipulationInertiaStarting</a></td>
<td align="left">Occurs when all contact points are lifted during a manipulation and the velocity of the manipulation is significant enough to initiate inertia behavior (translation and zoom continue after the input pointers are lifted).</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a></td>
<td align="left">Occurs when one or more input points have been initiated and subsequent motion (translation or zoom) has begun.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a></td>
<td align="left">Occurs after one or more input points have been initiated and subsequent motion (translation or zoom) is under way.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Events/PressingCompleted_Event.md">PressingCompleted</a></td>
<td align="left">Occurs when the system no longer considers the pointer to be over a tappable gesture recognizer.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Events/PressingStarted_Event.md">PressingStarted</a></td>
<td align="left">Occurs when the pointer begins a press gesture over a tappable gesture recognizer.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectGestureRecognizer/Events/PressingUpdated_Event.md">PressingUpdated</a></td>
<td align="left">Occurs as additional points are processed by the gesture recognizer during a press gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectGestureRecognizer/Events/Tapped_Event.md">Tapped</a></td>
<td align="left">Occurs when the Kinect for Windows sensor input is interpreted as a tap gesture.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EV"></span>

See also  
========  

<span id="ID4EX"></span>
#### Reference  

[WindowsPreview.Kinect.Input Namespace](../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectGestureRecognizer Class
RLTitle : KinectGestureRecognizer Class
KeywordK : KinectGestureRecognizer class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer
KeywordF : KinectGestureRecognizer
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer
KeywordA : T:WindowsPreview.Kinect.Input.KinectGestureRecognizer
AssetID : T:WindowsPreview.Kinect.Input.KinectGestureRecognizer
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer
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
