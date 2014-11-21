MatchCandidates.MatchPoses Property  
===================================  

Gets a collection of the camera poses in the database that were match candidates to the input depth frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
property IVectorView&lt;<a href="../../Matrix4x4_Structure.md">Matrix4x4</a>&gt;^ MatchPoses {  
         IVectorView&lt;<a href="../../Matrix4x4_Structure.md">Matrix4x4</a>&gt;^ get ();  
}</code></pre></td>
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
<td align="left"><pre><code>public IReadOnlyList&lt;<a href="../../Matrix4x4_Structure.md">Matrix4x4</a>&gt;MatchPoses { get; }</code></pre></td>
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
<td align="left"><pre><code>var matchPoses = matchCandidates.matchPoses;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[Matrix4x4](../../Matrix4x4_Structure.md)\>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[Matrix4x4](../../Matrix4x4_Structure.md)\>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[Matrix4x4](../../Matrix4x4_Structure.md)\>

The a collection of the camera poses.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[MatchCandidates Class](../../MatchCandidates_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MatchPoses Property
RLTitle : MatchCandidates.MatchPoses Property
KeywordK : MatchPoses property
KeywordK : MatchCandidates.MatchPoses property
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates.MatchPoses
KeywordF : MatchCandidates.MatchPoses
KeywordF : MatchPoses
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates.MatchPoses
KeywordA : P:Microsoft.Kinect.Fusion.MatchCandidates.MatchPoses
AssetID : P:Microsoft.Kinect.Fusion.MatchCandidates.MatchPoses
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.MatchCandidates.MatchPoses
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
