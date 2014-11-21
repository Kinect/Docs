PressableModel Class  
====================  

Maintains data and state for a pressable Kinect Toolkit input element. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class PressableModel sealed : <a href="IInputModel_Interface.md">IInputModel</a>, <a href="IPressableModel_Interface.md">IPressableModel</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class PressableModel : <a href="IInputModel_Interface.md">IInputModel</a>, <a href="IPressableModel_Interface.md">IPressableModel</a></code></pre></td>
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
<td align="left"><pre><code>var pressableModel = Microsoft.Kinect.Toolkit.Input.PressableModel;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**PressableModel** has the following members.  

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
<td align="left"><a href="PressableModel_Class/Constructor.md">PressableModel</a></td>
<td align="left">Overloaded. Initializes a new instance of the <a href="">PressableModel</a> class.</td>
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
<td align="left"><a href="PressableModel_Class/Properties/CapturedPointerId_Property.md">CapturedPointerId</a></td>
<td align="left">Gets the identifier of the <a href="../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint Class</a> that has captured the Kinect Toolkit input element.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Properties/Element_Property.md">Element</a></td>
<td align="left">Gets the object that represents the Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Properties/GestureRecognizer_Property.md">GestureRecognizer</a></td>
<td align="left">Gets the <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a> associated with the Kinect Toolkit input element.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Properties/HasCapture_Property.md">HasCapture</a></td>
<td align="left">Gets a boolean value indicating if the Kinect Toolkit input element is currently captured.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Properties/HasCaptureChanged_Property.md">HasCaptureChanged</a></td>
<td align="left">Gets a boolean value indicating if the capture status of the Kinect Toolkit input element has changed.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Properties/HoldProgress_Property.md">HoldProgress</a></td>
<td align="left">Gets a floating point value indicating the progress of a held press gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Properties/IsHolding_Property.md">IsHolding</a></td>
<td align="left">Gets a boolean value indicating whether the Kinect Toolkit input element has a press gesture currently being held.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Properties/IsManipulatable_Property.md">IsManipulatable</a></td>
<td align="left">Gets a boolean value indicating whether the Kinect Toolkit input element supports manipulation gestures.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Properties/IsPressingDown_Property.md">IsPressingDown</a></td>
<td align="left">Gets a boolean value indicating whether the Kinect Toolkit input element has a pressing down gesture in progress.</td>
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
<td align="left"><a href="PressableModel_Class/Methods/Attach_Method.md">Attach</a></td>
<td align="left">Attaches the Kinect Toolkit input element to the the specified <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a>.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Methods/CompleteGesture_Method.md">CompleteGesture</a></td>
<td align="left">Finalizes a gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Methods/Detach_Method.md">Detach</a></td>
<td align="left">Detaches the Kinect Toolkit input element from the specified <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a>.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Methods/ProcessPointerMove_Method.md">ProcessPointerMove</a></td>
<td align="left">Processes the movement of the pointer associated with the Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Methods/SetLocation_Method.md">SetLocation</a></td>
<td align="left">Overloaded. Sets the initial position of the pressable Kinect Toolkit input element.</td>
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
<td align="left"><a href="PressableModel_Class/Events/Holding_Event.md">Holding</a></td>
<td align="left">Occurs when a press gesture associated with the Kinect Toolkit input element is being held.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Events/PressingCompleted_Event.md">PressingCompleted</a></td>
<td align="left">Occurs when a press gesture associated with the Kinect Toolkit input element completes.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Events/PressingStarted_Event.md">PressingStarted</a></td>
<td align="left">Occurs when a press gesture associated with the Kinect Toolkit input element starts.</td>
</tr>
<tr class="even">
<td align="left"><a href="PressableModel_Class/Events/PressingUpdated_Event.md">PressingUpdated</a></td>
<td align="left">Occurs when a press gesture associated with the Kinect Toolkit input element is updated.</td>
</tr>
<tr class="odd">
<td align="left"><a href="PressableModel_Class/Events/Tapped_Event.md">Tapped</a></td>
<td align="left">Occurs when the Kinect Toolkit input element is tapped.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[Microsoft.Kinect.Toolkit.Input Namespace](../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PressableModel Class
RLTitle : PressableModel Class
KeywordK : PressableModel class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel
KeywordF : PressableModel
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel
KeywordA : T:Microsoft.Kinect.Toolkit.Input.PressableModel
AssetID : T:Microsoft.Kinect.Toolkit.Input.PressableModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.PressableModel
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
