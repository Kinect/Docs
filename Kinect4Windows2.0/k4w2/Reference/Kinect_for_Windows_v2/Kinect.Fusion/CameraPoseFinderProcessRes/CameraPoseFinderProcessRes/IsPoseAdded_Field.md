CameraPoseFinderProcessResult.IsPoseAdded Field  
===============================================  

A value indicating whether a new frame was added to the camera pose data. <span id="syntaxSection"></span>

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
bool IsPoseAdded</code></pre></td>
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
<td align="left"><pre><code>public bool IsPoseAdded</code></pre></td>
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
<td align="left"><pre><code>var isPoseAdded = cameraPoseFinderProcessResult.isPoseAdded;</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The [CameraPoseFinder](../../CameraPoseFinder_Class.md) only adds a new reference frame if the frame is sufficiently different from all other frames it is currently tracking. If a new frame is added, the value of this field will be true.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E4"></span>

See also  
========  

<span id="ID4E6"></span>
#### Reference  

[CameraPoseFinderProcessResult Structure](../../CameraPoseFinderProcessRes.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IsPoseAdded Field
RLTitle : CameraPoseFinderProcessResult.IsPoseAdded Field
KeywordK : IsPoseAdded field
KeywordK : CameraPoseFinderProcessResult.IsPoseAdded field
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult.IsPoseAdded
KeywordF : CameraPoseFinderProcessResult.IsPoseAdded
KeywordF : IsPoseAdded
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult.IsPoseAdded
KeywordA : F:Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult.IsPoseAdded
AssetID : F:Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult.IsPoseAdded
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult.IsPoseAdded
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
