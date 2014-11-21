INuiFusionMatchCandidates Interface  
===================================  

Used by the CameraPoseFinder::FindCameraPose method to provide access to the matched camera poses and their similarity measurements. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface INuiFusionMatchCandidates : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionMatchCandidates** has the following members.  

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
<td align="left"><a href="INuiFusionMatchCandidates/Methods/CalculateMinimumDistance.md">CalculateMinimumDistance</a></td>
<td align="left">Calculates the distance between the input depth frame and the most similar pose candidate in the pose database.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/GetMatchPoses_Method.md">GetMatchPoses</a></td>
<td align="left">Gets a collection of the camera poses in the database that were match candidates to the input depth frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/GetMatchSimilarities_Method.md">GetMatchSimilarities</a></td>
<td align="left">Gets a collection of the match similarity measurements for the match candidates returned by the MatchPoses property.</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/MatchPoseCount_Method.md">MatchPoseCount</a></td>
<td align="left">Gets the number of camera poses in the database that were match candidates to the input depth frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/MatchSimilarityCount_Method.md">MatchSimilarityCount</a></td>
<td align="left">Gets the number of match similarity measurements.</td>
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
TOCTitle : INuiFusionMatchCandidates Interface
RLTitle : INuiFusionMatchCandidates Interface
KeywordK : INuiFusionMatchCandidates interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionMatchCandidates
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
KeywordA : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
AssetID : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
