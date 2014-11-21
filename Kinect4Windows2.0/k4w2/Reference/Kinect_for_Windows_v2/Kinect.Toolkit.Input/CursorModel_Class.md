CursorModel Class  
=================  

Maintains the data and state for a Kinect cursor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class CursorModel sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class CursorModel : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var cursorModel = Microsoft.Kinect.Toolkit.Input.CursorModel;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**CursorModel** has the following members.  

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
<td align="left"><a href="CursorModel_Class/Constructor.md">CursorModel</a></td>
<td align="left">Creates a new instance of the <a href="">CursorModel</a> class.</td>
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
<td align="left"><a href="CursorModel_Class/Properties/ClampedPressExtent_Property.md">ClampedPressExtent</a></td>
<td align="left">Gets the extent of a clamped press gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Properties/CurrentBackgroundFrame.md">CurrentBackgroundFrame</a></td>
<td align="left">Gets the current frame of the background sprite animation.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorModel_Class/Properties/CurrentForegroundFrame.md">CurrentForegroundFrame</a></td>
<td align="left">Gets the current frame of the foreground sprite animation.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Properties/CursorSpriteSheetDefinition.md">CursorSpriteSheetDefinition</a></td>
<td align="left">Gets an object that defines the format of the sprite sheet associated with the cursor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorModel_Class/Properties/CursorState_Property.md">CursorState</a></td>
<td align="left">Gets a value indicating the current state of the cursor.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Properties/HandType_Property.md">HandType</a></td>
<td align="left">Gets a value indicating the type of the hand associated with the cursor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorModel_Class/Properties/HoldProgress_Property.md">HoldProgress</a></td>
<td align="left">Gets a value indicating the progress of a hold gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Properties/IsAnimationComplete_Property.md">IsAnimationComplete</a></td>
<td align="left">Gets a value indicating if the cursor animation is complete.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorModel_Class/Properties/PointerId_Property.md">PointerId</a></td>
<td align="left">Gets the identifier of the <a href="../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint Class</a> associated with the cursor.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Properties/Position_Property.md">Position</a></td>
<td align="left">Gets the current position of the cursor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorModel_Class/Properties/PressExtent_Property.md">PressExtent</a></td>
<td align="left">Gets the extent of a press gesture.</td>
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
<td align="left"><a href="CursorModel_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Disposes of the object and associated resources.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Methods/StartTimeBasedAnimation.md">StartTimeBasedAnimation</a></td>
<td align="left">Starts the cursor's time-based sprite animation.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorModel_Class/Methods/Tick_Method.md">Tick</a></td>
<td align="left">Increments the current frames of cursor's sprite animation.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorModel_Class/Methods/Update_Method.md">Update</a></td>
<td align="left">Updates the position and state of the cursor.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EZ"></span>

See also  
========  

<span id="ID4E2"></span>
#### Reference  

[Microsoft.Kinect.Toolkit.Input Namespace](../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CursorModel Class
RLTitle : CursorModel Class
KeywordK : CursorModel class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorModel
KeywordF : CursorModel
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorModel
KeywordA : T:Microsoft.Kinect.Toolkit.Input.CursorModel
AssetID : T:Microsoft.Kinect.Toolkit.Input.CursorModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.CursorModel
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
