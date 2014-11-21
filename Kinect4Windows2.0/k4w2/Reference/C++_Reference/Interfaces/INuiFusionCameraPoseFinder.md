INuiFusionCameraPoseFinder Interface  
====================================  

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
<td align="left"><pre><code>interface INuiFusionCameraPoseFinder : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionCameraPoseFinder** has the following members.  

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
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/FindCameraPose_Method.md">FindCameraPose</a></td>
<td align="left">Retrieves the poses in the camera pose finder database that are most similar to the current camera input.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/GetCameraPoseFinderParamet.md">GetCameraPoseFinderParameters</a></td>
<td align="left">Gets the parameters associated with the CameraPoseFinder.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/GetStoredPoseCount_Method.md">GetStoredPoseCount</a></td>
<td align="left">Gets the number of poses stored by the CameraPoseFinder.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/LoadCameraPoseFinderDatabase.md">LoadCameraPoseFinderDatabase</a></td>
<td align="left">Loads a previously-saved camera pose finder database from disk.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/ProcessFrame_Method.md">ProcessFrame</a></td>
<td align="left">Adds the specified camera frame to the camera pose finder database if the frame differs enough from poses that already exist in the database.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/ResetCameraPoseFinder_Method.md">ResetCameraPoseFinder</a></td>
<td align="left">Clears the CameraPoseFinder.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/SaveCameraPoseFinderDatabase.md">SaveCameraPoseFinderDatabase</a></td>
<td align="left">Saves the camera pose finder database to disk.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionCameraPoseFinder Interface
RLTitle : INuiFusionCameraPoseFinder Interface
KeywordK : INuiFusionCameraPoseFinder interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionCameraPoseFinder
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
KeywordA : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
AssetID : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
