CameraPoseFinder Class  
======================  

Encapsulates camera pose finder creation, updating, and pose-finding functions. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class CameraPoseFinder sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class CameraPoseFinder</code></pre></td>
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
<td align="left"><pre><code>var cameraPoseFinder = Microsoft.Kinect.Fusion.CameraPoseFinder;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**CameraPoseFinder** has the following members.  

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
<td align="left"><a href="CameraPoseFinder_Class/Constructor.md">CameraPoseFinder</a></td>
<td align="left">Overloaded. Initializes a new instance of the <a href="">CameraPoseFinder</a>.</td>
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
<td align="left"><a href="CameraPoseFinder_Class/Properties/CameraPoseFinderParameters.md">CameraPoseFinderParameters</a></td>
<td align="left">Gets the parameters associated with the <a href="">CameraPoseFinder</a>.</td>
</tr>
<tr class="even">
<td align="left"><a href="CameraPoseFinder_Class/Properties/StoredPoseCount_Property.md">StoredPoseCount</a></td>
<td align="left">Gets the number of poses stored by the <a href="">CameraPoseFinder</a>.</td>
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
<td align="left"><a href="CameraPoseFinder_Class/Methods/FindCameraPose_Method.md">FindCameraPose</a></td>
<td align="left">Retrieves the poses in the camera pose finder database that are most similar to the current camera input.</td>
</tr>
<tr class="even">
<td align="left"><a href="CameraPoseFinder_Class/Methods/LoadCameraPoseFinderDatabase.md">LoadCameraPoseFinderDatabase</a></td>
<td align="left">Loads a previously-saved camera pose finder database from disk.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CameraPoseFinder_Class/Methods/ProcessFrame_Method.md">ProcessFrame</a></td>
<td align="left">Adds the specified camera frame to the camera pose finder database if the frame differs enough from poses that already exist in the database.</td>
</tr>
<tr class="even">
<td align="left"><a href="CameraPoseFinder_Class/Methods/ResetCameraPoseFinder_Method.md">ResetCameraPoseFinder</a></td>
<td align="left">Clears the <strong>CameraPoseFinder</strong>.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CameraPoseFinder_Class/Methods/SaveCameraPoseFinderDatabase.md">SaveCameraPoseFinderDatabase</a></td>
<td align="left">Saves the camera pose finder database to disk.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EV"></span>

See also  
========  

<span id="ID4EX"></span>
#### Reference  

[Microsoft.Kinect.Fusion Namespace](../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraPoseFinder Class
RLTitle : CameraPoseFinder Class
KeywordK : CameraPoseFinder class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder
KeywordF : CameraPoseFinder
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder
KeywordA : T:Microsoft.Kinect.Fusion.CameraPoseFinder
AssetID : T:Microsoft.Kinect.Fusion.CameraPoseFinder
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinder
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
