KinectRegion Class  
==================  

Represents a XAML control which provides a Kinect hand cursor and interactivity with elements contained within the KinectRegion. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class KinectRegion sealed : public ContentControl</code></pre></td>
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
<td align="left"><pre><code>public sealed class KinectRegion : ContentControl</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**KinectRegion** has the following members.  

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
<td align="left"><a href="KinectRegion_Class/Constructor.md">KinectRegion</a></td>
<td align="left">Initializes a new instance of the <a href="">KinectRegion</a> class.</td>
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
<td align="left"><a href="KinectRegion_Class/Properties/Bounds_Property.md">Bounds</a></td>
<td align="left">Gets the bounds of the control.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Properties/CursorSpriteSheetDefinition.md">CursorSpriteSheetDefinition</a></td>
<td align="left">Gets the cursor sprite sheet definition for the control.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Properties/DefaultKinectSound_Property.md">DefaultKinectSound</a></td>
<td align="left">Gets the default sounds for the control.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Properties/DefaultSpriteSheet_Property.md">DefaultSpriteSheet</a></td>
<td align="left">Gets the default sprite sheet for the control.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Properties/InputPointerManager_Property.md">InputPointerManager</a></td>
<td align="left">Gets the <a href="../Kinect.Toolkit.Input/InputPointerManager_Class.md">InputPointerManager</a> associated with the control.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Properties/IsKinectSoundEnabled.md">IsKinectSoundEnabled</a></td>
<td align="left">Gets or sets a value indicating whether Kinect sound is enabled.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Properties/IsPressTargetProperty.md">IsPressTargetProperty</a></td>
<td align="left">Identifies the IsPressTarget dependency property.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Properties/KinectControllerProperty.md">KinectControllerProperty</a></td>
<td align="left">Identifies the KinectController dependency property.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Properties/KinectEngagementManager.md">KinectEngagementManager</a></td>
<td align="left">Gets the Kinect engagement manager associated with the control.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Properties/KinectPressInsetProperty.md">KinectPressInsetProperty</a></td>
<td align="left">Idenitifies the KinectPressInset dependency property.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Properties/KinectSoundDefinition.md">KinectSoundDefinition</a></td>
<td align="left">Gets or sets the <a href="KinectSoundDefinition_Class.md">KinectSoundDefinition</a> object for the control.</td>
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
<td align="left"><a href="KinectRegion_Class/Methods/GetIsCursorVisible_Method.md">GetIsCursorVisible</a></td>
<td align="left">Gets a value indicating whether the cursor is visible.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Methods/GetIsPressTarget_Method.md">GetIsPressTarget</a></td>
<td align="left">Gets a value indicating if the control is a press target.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Methods/GetKinectPressInset_Method.md">GetKinectPressInset</a></td>
<td align="left">Gets the thickness of the inset border displayed during a press gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Methods/GetManipulationProgress.md">GetManipulationProgress</a></td>
<td align="left">Gets a value indicating the current progress of a manipulation gesture.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Methods/SetIsCursorVisible_Method.md">SetIsCursorVisible</a></td>
<td align="left">Sets a value indicating whether the cursor is visible.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Methods/SetIsPressTarget_Method.md">SetIsPressTarget</a></td>
<td align="left">Sets a value indicating whether the control is a press target.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Methods/SetKinectOnePersonManualEn.md">SetKinectOnePersonManualEngagement</a></td>
<td align="left">Instructs the region to track one body/hand pair that is specified by the application as currently engaged.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Methods/SetKinectOnePersonSystemEn.md">SetKinectOnePersonSystemEngagement</a></td>
<td align="left">Instructs the region to track one body/hand pair that is dynamically determined by the system as currently engaged.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Methods/SetKinectPressInset_Method.md">SetKinectPressInset</a></td>
<td align="left">Sets the thickness of the inset border displayed during a press gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Methods/SetKinectTwoPersonManualEn.md">SetKinectTwoPersonManualEngagement</a></td>
<td align="left">Instructs the region to track two body/hand pairs that are specified by the application as currently engaged.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectRegion_Class/Methods/SetKinectTwoPersonSystemEn.md">SetKinectTwoPersonSystemEngagement</a></td>
<td align="left">Instructs the region to track two body/hand pairs that are dynamically determined by the system as currently engaged.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectRegion_Class/Methods/SetManipulationProgress.md">SetManipulationProgress</a></td>
<td align="left">Sets the manipulation progress for the <a href="">KinectRegion</a>.</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Xaml.Controls  
**Assembly:** (in )  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[Microsoft.Kinect.Xaml.Controls Namespace](../Kinect.Xaml.Controls.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectRegion Class
RLTitle : KinectRegion Class
KeywordK : KinectRegion class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Xaml.Controls.KinectRegion
KeywordF : KinectRegion
KeywordF : Microsoft.Kinect.Xaml.Controls.KinectRegion
KeywordA : T:Microsoft.Kinect.Xaml.Controls.KinectRegion
AssetID : T:Microsoft.Kinect.Xaml.Controls.KinectRegion
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Xaml.Controls.KinectRegion
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
