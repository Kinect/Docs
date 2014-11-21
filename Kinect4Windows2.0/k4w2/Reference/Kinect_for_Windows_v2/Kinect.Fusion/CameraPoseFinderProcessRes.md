CameraPoseFinderProcessResult Structure  
=======================================  

Represents the results of a [ProcessFrame](CameraPoseFinder_Class/Methods/ProcessFrame_Method.md) operation. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public value struct CameraPoseFinderProcessResult</code></pre></td>
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
<td align="left"><pre><code>public struct CameraPoseFinderProcessResult</code></pre></td>
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
<td align="left"><pre><code>var cameraPoseFinderProcessResult = {  
      isHistoryTrimmed : /* Your value */,   
      isPoseAdded : /* Your value */  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**CameraPoseFinderProcessResult** has the following members.  

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
<td align="left"><a href="CameraPoseFinderProcessRes/CameraPoseFinderProcessRes/IsHistoryTrimmed_Field.md">IsHistoryTrimmed</a></td>
<td align="left">A value indicating wether the camera pose finder removed frames from the frame history for performance reasons.</td>
</tr>
<tr class="even">
<td align="left"><a href="CameraPoseFinderProcessRes/CameraPoseFinderProcessRes/IsPoseAdded_Field.md">IsPoseAdded</a></td>
<td align="left">A value indicating whether a new frame was added to the camera pose data.</td>
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
TOCTitle : CameraPoseFinderProcessResult Structure
RLTitle : CameraPoseFinderProcessResult Structure
KeywordK : CameraPoseFinderProcessResult structure, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult
KeywordF : CameraPoseFinderProcessResult
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult
KeywordA : T:Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult
AssetID : T:Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinderProcessResult
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
