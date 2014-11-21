InputPointerManager Class  
=========================  

Handles the routing of [KinectPointerPoint Class](../Kinect.Input/KinectPointerPoint_Class.md) objects to the correct [KinectGestureRecognizer Class](../Kinect.Input/KinectGestureRecognizer.md) objects and keeps track of the currently captured Kinect Tookit input elements. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class InputPointerManager sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class InputPointerManager : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var inputPointerManager = Microsoft.Kinect.Toolkit.Input.InputPointerManager;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**InputPointerManager** has the following members.  

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
<td align="left"><a href="InputPointerManager_Class/InputPointerManager.md">InputPointerManager</a></td>
<td align="left">Overloaded. Initializes a new instance of the <a href="">InputPointerManager</a> class.</td>
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
<td align="left"><a href="InputPointerManager_Class/Properties/KinectEngagementManager.md">KinectEngagementManager</a></td>
<td align="left">Gets the <a href="IKinectEngagementManager.md">IKinectEngagementManager</a> object associated with the input pointer manager.</td>
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
<td align="left"><a href="InputPointerManager_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Disposes of the object and associated resources.</td>
</tr>
<tr class="even">
<td align="left"><a href="InputPointerManager_Class/Methods/CompleteGesture_Method.md">CompleteGesture</a></td>
<td align="left">Completes a gesture associated with the specified <a href="../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint Class</a> and Kinect Toolkit input element.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InputPointerManager_Class/Methods/CompleteGestures_Method.md">CompleteGestures</a></td>
<td align="left">Overloaded. Completes all in-progress gestures.</td>
</tr>
<tr class="even">
<td align="left"><a href="InputPointerManager_Class/Methods/GetCapturedInputModel_Method.md">GetCapturedInputModel</a></td>
<td align="left">Gets the <a href="HitTestResult_Class.md">HitTestResult</a> object containing the captured Kinect Tookit input elements associated with the specified <a href="../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint Class</a>.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InputPointerManager_Class/Methods/HandlePointerAsCursor_Method.md">HandlePointerAsCursor</a></td>
<td align="left">Instructs the input pointer manager to handle the pointer as a cursor.</td>
</tr>
<tr class="even">
<td align="left"><a href="InputPointerManager_Class/Methods/ProcessInertia_Method.md">ProcessInertia</a></td>
<td align="left">Instructs the input pointer manager to process gesture interia.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InputPointerManager_Class/Methods/SetKinectOnePersonManualEn.md">SetKinectOnePersonManualEngagement</a></td>
<td align="left">Instructs the <a href="IKinectEngagementManager.md">IKinectEngagementManager Interface</a> to track one body/hand pair that is manually specified by the application as currently engaged.</td>
</tr>
<tr class="even">
<td align="left"><a href="InputPointerManager_Class/Methods/SetKinectOnePersonSystemEn.md">SetKinectOnePersonSystemEngagement</a></td>
<td align="left">Instructs the <a href="IKinectEngagementManager.md">IKinectEngagementManager Interface</a> to track one body/hand pair that are dynamically determined by the system as currently engaged.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InputPointerManager_Class/Methods/SetKinectTwoPersonManualEn.md">SetKinectTwoPersonManualEngagement</a></td>
<td align="left">Instructs the <a href="IKinectEngagementManager.md">IKinectEngagementManager Interface</a> to track two body/hand pairs that are manually specified by the application as currently engaged.</td>
</tr>
<tr class="even">
<td align="left"><a href="InputPointerManager_Class/Methods/SetKinectTwoPersonSystemEn.md">SetKinectTwoPersonSystemEngagement</a></td>
<td align="left">Instructs the <a href="IKinectEngagementManager.md">IKinectEngagementManager Interface</a> to track two body/hand pairs that are dynamically determined by the system as currently engaged.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InputPointerManager_Class/Methods/TransformInputPointerCoord.md">TransformInputPointerCoordinatesToWindowCoordinates</a></td>
<td align="left">Transforms a pointer coordinate that is normalized between 0 and 1.0 into a pixel-based window coordinate.</td>
</tr>
<tr class="even">
<td align="left"><a href="InputPointerManager_Class/Methods/TransformWindowCoordinates.md">TransformWindowCoordinatesToInputPointerCoordinates</a></td>
<td align="left">Transforms a pixel-based window coordinate into a pointer coordinate that is normalized between 0 and 1.0.</td>
</tr>
<tr class="odd">
<td align="left"><a href="InputPointerManager_Class/Methods/Update_Method.md">Update</a></td>
<td align="left">Updates the data in the input pointer manager for the current frame.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[Microsoft.Kinect.Toolkit.Input Namespace](../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : InputPointerManager Class
RLTitle : InputPointerManager Class
KeywordK : InputPointerManager class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager
KeywordF : InputPointerManager
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager
KeywordA : T:Microsoft.Kinect.Toolkit.Input.InputPointerManager
AssetID : T:Microsoft.Kinect.Toolkit.Input.InputPointerManager
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.InputPointerManager
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
