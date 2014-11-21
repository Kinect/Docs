CameraPoseFinderParameters Structure  
====================================  

Defines the number of poses and feature sample locations used by the [CameraPoseFinder](CameraPoseFinder_Class.md) class. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public value struct CameraPoseFinderParameters</code></pre></td>
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
<td align="left"><pre><code>public struct CameraPoseFinderParameters</code></pre></td>
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
<td align="left"><pre><code>var cameraPoseFinderParameters = {  
      featureSampleLocationsPerFrameCount : /* Your value */,   
      maxDepthThreshold : /* Your value */,   
      maxPoseHistoryCount : /* Your value */  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**CameraPoseFinderParameters** has the following members.  

<span id="publicfieldsSection"></span>

Fields  
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
<td align="left"><a href="CameraPoseFinderParameters/CameraPoseFinderParameters/FeatureSampleLocationsPerF.md">FeatureSampleLocationsPerFrameCount</a></td>
<td align="left">The number of features to extract per frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="CameraPoseFinderParameters/CameraPoseFinderParameters/MaxDepthThreshold_Field.md">MaxDepthThreshold</a></td>
<td align="left">The maximum depth to use when choosing a threshold value for each of the sample features in a key frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CameraPoseFinderParameters/CameraPoseFinderParameters/MaxPoseHistoryCount_Field.md">MaxPoseHistoryCount</a></td>
<td align="left">The maximum size of the camera pose finder pose history database.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EY"></span>

See also  
========  

<span id="ID4E1"></span>
#### Reference  

[Microsoft.Kinect.Fusion Namespace](../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraPoseFinderParameters Structure
RLTitle : CameraPoseFinderParameters Structure
KeywordK : CameraPoseFinderParameters structure, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderParameters
KeywordF : CameraPoseFinderParameters
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderParameters
KeywordA : T:Microsoft.Kinect.Fusion.CameraPoseFinderParameters
AssetID : T:Microsoft.Kinect.Fusion.CameraPoseFinderParameters
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinderParameters
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
