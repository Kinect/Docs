AlignmentResult.AlignmentEnergy Property  
========================================  

Gets threshold in the range [0.0f, 1.0f] that describes how well the observed frame aligns to the model with the calculated pose (mean distance between matching points in the point clouds). <span id="syntaxSection"></span>

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
property float32 AlignmentEnergy {  
         float32 get ();  
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
<td align="left"><pre><code>public float AlignmentEnergy { get; }</code></pre></td>
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
<td align="left"><pre><code>var alignmentEnergy = alignmentResult.alignmentEnergy;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: float32  
Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
Type: Number  

The alignment energy.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[AlignmentResult Class](../../AlignmentResult_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AlignmentEnergy Property
RLTitle : AlignmentResult.AlignmentEnergy Property
KeywordK : AlignmentEnergy property
KeywordK : AlignmentResult.AlignmentEnergy property
KeywordF : Microsoft.Kinect.Fusion.AlignmentResult.AlignmentEnergy
KeywordF : AlignmentResult.AlignmentEnergy
KeywordF : AlignmentEnergy
KeywordF : Microsoft.Kinect.Fusion.AlignmentResult.AlignmentEnergy
KeywordA : P:Microsoft.Kinect.Fusion.AlignmentResult.AlignmentEnergy
AssetID : P:Microsoft.Kinect.Fusion.AlignmentResult.AlignmentEnergy
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.AlignmentResult.AlignmentEnergy
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
