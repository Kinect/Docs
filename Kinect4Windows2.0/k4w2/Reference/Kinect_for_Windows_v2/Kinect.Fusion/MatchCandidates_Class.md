MatchCandidates Class  
=====================  

Used by the [CameraPoseFinder.FindCameraPose](CameraPoseFinder_Class/Methods/FindCameraPose_Method.md) method to provide access to the matched camera poses and their similarity measurements. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class MatchCandidates sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class MatchCandidates</code></pre></td>
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
<td align="left"><pre><code>var matchCandidates = Microsoft.Kinect.Fusion.MatchCandidates;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**MatchCandidates** has the following members.  

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
<td align="left"><a href="MatchCandidates_Class/Properties/MatchPoses_Property.md">MatchPoses</a></td>
<td align="left">Gets a collection of the camera poses in the database that were match candidates to the input depth frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="MatchCandidates_Class/Properties/MatchSimilarities_Property.md">MatchSimilarities</a></td>
<td align="left">Gets a collection of the match similarity measurements for the match candidates returned by the <a href="MatchCandidates_Class/Properties/MatchPoses_Property.md">MatchPoses</a> property.</td>
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
<td align="left"><a href="MatchCandidates_Class/Methods/CalculateMinimumDistance.md">CalculateMinimumDistance</a></td>
<td align="left">Calculates the distance between the input depth frame and the most similar pose candidate in the pose database.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E1"></span>

See also  
========  

<span id="ID4E3"></span>
#### Reference  

[Microsoft.Kinect.Fusion Namespace](../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MatchCandidates Class
RLTitle : MatchCandidates Class
KeywordK : MatchCandidates class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates
KeywordF : MatchCandidates
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates
KeywordA : T:Microsoft.Kinect.Fusion.MatchCandidates
AssetID : T:Microsoft.Kinect.Fusion.MatchCandidates
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.MatchCandidates
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
