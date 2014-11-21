MatchCandidates.MatchSimilarities Property  
==========================================  

Gets a collection of the match similarity measurements for the match candidates returned by the [MatchPoses](MatchPoses_Property.md) property. <span id="syntaxSection"></span>

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
property IVectorView&lt;float32&gt;^ MatchSimilarities {  
         IVectorView&lt;float32&gt;^ get ();  
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
<td align="left"><pre><code>public IReadOnlyList&lt;float&gt;MatchSimilarities { get; }</code></pre></td>
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
<td align="left"><pre><code>var matchSimilarities = matchCandidates.matchSimilarities;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EW"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<float32\>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[float](http://msdn.microsoft.com/en-us/library/system.single.aspx)\>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<Number\>

Returns a read-only collection of the similarity measurements. Similarity measurements are a count of how many features were matched, normalized to a value in the range [0.0f, 1.0f] by dividing by the number of sample locations per frame. Larger values indicate more similarity between the input and the match candidate pose.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EFB"></span>

See also  
========  

<span id="ID4EHB"></span>
#### Reference  

[MatchCandidates Class](../../MatchCandidates_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MatchSimilarities Property
RLTitle : MatchCandidates.MatchSimilarities Property
KeywordK : MatchSimilarities property
KeywordK : MatchCandidates.MatchSimilarities property
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates.MatchSimilarities
KeywordF : MatchCandidates.MatchSimilarities
KeywordF : MatchSimilarities
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates.MatchSimilarities
KeywordA : P:Microsoft.Kinect.Fusion.MatchCandidates.MatchSimilarities
AssetID : P:Microsoft.Kinect.Fusion.MatchCandidates.MatchSimilarities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.MatchCandidates.MatchSimilarities
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
