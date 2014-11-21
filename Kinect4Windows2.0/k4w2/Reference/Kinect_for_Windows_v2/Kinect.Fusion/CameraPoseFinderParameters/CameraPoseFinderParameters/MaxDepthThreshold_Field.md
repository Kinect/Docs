CameraPoseFinderParameters.MaxDepthThreshold Field  
==================================================  

The maximum depth to use when choosing a threshold value for each of the sample features in a key frame. <span id="syntaxSection"></span>

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
float32 MaxDepthThreshold</code></pre></td>
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
<td align="left"><pre><code>public float MaxDepthThreshold</code></pre></td>
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
<td align="left"><pre><code>var maxDepthThreshold = cameraPoseFinderParameters.maxDepthThreshold;</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The maximum depth to use when choosing a threshold value for each of the sample features in a key frame, in meters. The minumum value for this threshold is 0.4f. The maximum value for this threshold is the closest working distance that you expect in your scenario (for example, if all of your reconstruction will be within two meters, set this value to 2.0f).  

Setting a large threshold for this value can make the system less discriminative. Long-distance scenarios will require you to implement more features to maintain matching performance.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[CameraPoseFinderParameters Structure](../../CameraPoseFinderParameters.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : MaxDepthThreshold Field
RLTitle : CameraPoseFinderParameters.MaxDepthThreshold Field
KeywordK : MaxDepthThreshold field
KeywordK : CameraPoseFinderParameters.MaxDepthThreshold field
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderParameters.MaxDepthThreshold
KeywordF : CameraPoseFinderParameters.MaxDepthThreshold
KeywordF : MaxDepthThreshold
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderParameters.MaxDepthThreshold
KeywordA : F:Microsoft.Kinect.Fusion.CameraPoseFinderParameters.MaxDepthThreshold
AssetID : F:Microsoft.Kinect.Fusion.CameraPoseFinderParameters.MaxDepthThreshold
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinderParameters.MaxDepthThreshold
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
