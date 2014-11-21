MatchCandidates.CalculateMinimumDistance Method  
===============================================  

Calculates the distance between the input depth frame and the most similar pose candidate in the pose database. <span id="syntaxSection"></span>

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
void CalculateMinimumDistance(  
         out float32 minimumDisatance  
)</code></pre></td>
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
<td align="left"><pre><code>public void CalculateMinimumDistance (  
         out float minimumDisatance  
)</code></pre></td>
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
<td align="left"><pre><code>matchCandidates.calculateMinimumDistance();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*minimumDisatance*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

Returns a floating-point value that contains the minimum distance measure. This value is in the range [0.0f, 1.0f], with smaller values indicating higher similarity and larger values indicating less similarity.  

<span id="remarks"></span>

Remarks  
=======  

You can regulate how different the poses in the database are by calling the [CameraPoseFinder.ProcessFrame](../../CameraPoseFinder_Class/Methods/ProcessFrame_Method.md) method only when this value exceeds a set threshold.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EGB"></span>

See also  
========  

<span id="ID4EIB"></span>
#### Reference  

[MatchCandidates Class](../../MatchCandidates_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculateMinimumDistance Method
RLTitle : MatchCandidates.CalculateMinimumDistance Method
KeywordK : CalculateMinimumDistance method
KeywordK : MatchCandidates.CalculateMinimumDistance method
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates.CalculateMinimumDistance
KeywordF : MatchCandidates.CalculateMinimumDistance
KeywordF : CalculateMinimumDistance
KeywordF : Microsoft.Kinect.Fusion.MatchCandidates.CalculateMinimumDistance(System.Single@)
KeywordA : M:Microsoft.Kinect.Fusion.MatchCandidates.CalculateMinimumDistance(System.Single@)
AssetID : M:Microsoft.Kinect.Fusion.MatchCandidates.CalculateMinimumDistance(System.Single@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.MatchCandidates.CalculateMinimumDistance
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
