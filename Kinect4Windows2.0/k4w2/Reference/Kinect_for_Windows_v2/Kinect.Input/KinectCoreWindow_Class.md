KinectCoreWindow Class  
======================  

Represents a Kinect for Windows app with input events and basic user interface behaviors. Only 1 core window is in “focus” at any one time, and that one gets the pointers and related events. The coordinate space of the window is normalized to the [0,1] range in both dimensions. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class KinectCoreWindow sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class KinectCoreWindow</code></pre></td>
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
<td align="left"><pre><code>var kinectCoreWindow = WindowsPreview.Kinect.Input.KinectCoreWindow;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**KinectCoreWindow** has the following members.  

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
<td align="left"><a href="KinectCoreWindow_Class/Properties/KinectEngagementMode.md">KinectEngagementMode</a></td>
<td align="left">Gets the current Kinect engagement mode.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectCoreWindow_Class/Properties/KinectManualEngagedHands.md">KinectManualEngagedHands</a></td>
<td align="left">Gets a list of body hand pairs that are manually engaged.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectCoreWindow_Class/Properties/MaximumKinectEngagedPerson.md">MaximumKinectEngagedPersonCount</a></td>
<td align="left">Gets the maximum number of users that can be tracked as engaged at one time.</td>
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
<td align="left"><a href="KinectCoreWindow_Class/Methods/GetForCurrentThread_Method.md">GetForCurrentThread</a></td>
<td align="left">Gets the <a href="">KinectCoreWindow</a> for the current thread.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectCoreWindow_Class/Methods/OverrideKinectInteractionM.md">OverrideKinectInteractionMode</a></td>
<td align="left">Overrides the current interaction mode.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectCoreWindow_Class/Methods/SetKinectOnePersonManualEn.md">SetKinectOnePersonManualEngagement</a></td>
<td align="left">Sets the engagement mode to one person manual engagement.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectCoreWindow_Class/Methods/SetKinectOnePersonSystemEn.md">SetKinectOnePersonSystemEngagement</a></td>
<td align="left">Sets the engagement mode to one person system engagement.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectCoreWindow_Class/Methods/SetKinectTwoPersonManualEn.md">SetKinectTwoPersonManualEngagement</a></td>
<td align="left">Sets the engagement mode to two person manual engagement.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectCoreWindow_Class/Methods/SetKinectTwoPersonSystemEn.md">SetKinectTwoPersonSystemEngagement</a></td>
<td align="left">Sets the engagement mode to two person system engagement.</td>
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
<td align="left"><a href="KinectCoreWindow_Class/Events/PointerEntered_Event.md">PointerEntered</a></td>
<td align="left">Occurs when a pointer ID is first seen by the window.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectCoreWindow_Class/Events/PointerExited_Event.md">PointerExited</a></td>
<td align="left">Occurs when a pointer moves outside the bounding box of the <a href="">KinectCoreWindow</a>.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectCoreWindow_Class/Events/PointerMoved_Event.md">PointerMoved</a></td>
<td align="left">Occurs when a pointer ID seen by the window moves.</td>
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
TOCTitle : KinectCoreWindow Class
RLTitle : KinectCoreWindow Class
KeywordK : KinectCoreWindow class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow
KeywordF : KinectCoreWindow
KeywordF : WindowsPreview.Kinect.Input.KinectCoreWindow
KeywordA : T:WindowsPreview.Kinect.Input.KinectCoreWindow
AssetID : T:WindowsPreview.Kinect.Input.KinectCoreWindow
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectCoreWindow
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
