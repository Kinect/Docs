IInputModel Interface  
=====================  

The base interface implemented by the [ManipulatableModel](ManipulatableModel_Class.md) and [PressableModel](PressableModel_Class.md) Kinect Toolkit input elements. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public interface class IInputModel</code></pre></td>
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
<td align="left"><pre><code>public interface IInputModel</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IInputModel** has the following members.  

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
<td align="left"><a href="IInputModel_Interface/Properties/CapturedPointerId_Property.md">CapturedPointerId</a></td>
<td align="left">Gets the identifier of the <a href="../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint Class</a> with which the Kinect Toolkit input element was captured.</td>
</tr>
<tr class="even">
<td align="left"><a href="IInputModel_Interface/Properties/Element_Property.md">Element</a></td>
<td align="left">Gets the object that represents the Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInputModel_Interface/Properties/GestureRecognizer_Property.md">GestureRecognizer</a></td>
<td align="left">Gets or sets the <a href="../Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer Class</a> object associated with the Kinect Toolkit input element.</td>
</tr>
<tr class="even">
<td align="left"><a href="IInputModel_Interface/Properties/HasCapture_Property.md">HasCapture</a></td>
<td align="left">Gets an boolean value indicating whether the Kinect Toolkit input element has been captured with a gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInputModel_Interface/Properties/HasCaptureChanged_Property.md">HasCaptureChanged</a></td>
<td align="left">Gets a value indicating whether the capture status of the Kinect Toolkit input element has changed.</td>
</tr>
<tr class="even">
<td align="left"><a href="IInputModel_Interface/Properties/IsManipulatable_Property.md">IsManipulatable</a></td>
<td align="left">Gets a value indicating whether the associated Kinect Toolkit input element supports manipulation gestures.</td>
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
<td align="left"><a href="IInputModel_Interface/Methods/CompleteGesture_Method.md">CompleteGesture</a></td>
<td align="left">Completes the gesture associated with Kinect Toolkit input element.</td>
</tr>
<tr class="even">
<td align="left"><a href="IInputModel_Interface/Methods/ProcessPointerMove_Method.md">ProcessPointerMove</a></td>
<td align="left">Processes the movement of the pointer associated with the Kinect Toolkit input element.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EBB"></span>

See also  
========  

<span id="ID4EDB"></span>
#### Reference  

[Microsoft.Kinect.Toolkit.Input Namespace](../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IInputModel Interface
RLTitle : IInputModel Interface
KeywordK : IInputModel interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Toolkit.Input.IInputModel
KeywordF : IInputModel
KeywordF : Microsoft.Kinect.Toolkit.Input.IInputModel
KeywordA : T:Microsoft.Kinect.Toolkit.Input.IInputModel
AssetID : T:Microsoft.Kinect.Toolkit.Input.IInputModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.IInputModel
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
