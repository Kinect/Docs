FrameEdges Enumeration  
======================  

Identifies if the user's body is visible by indicating any portion of the user that is not in the camera's field of view. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>[FlagsAttribute]  
public enum class FrameEdges</code></pre></td>
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum FrameEdges</code></pre></td>
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
<td align="left"><pre><code>var frameEdges = WindowsPreview.Kinect.FrameEdges.bottom;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E3B"></span>

Members  
=======  

| Member     | Value | Description                                                                              |
|------------|-------|------------------------------------------------------------------------------------------|
| **Bottom** | 8     | The user's body extends below the camera's field of view.                                |
| **Left**   | 2     | The user's body extends to the left of the camera's field of view.                       |
| **None**   | 0     | None of the user's body is out of the camera's field of view, the user is fully visible. |
| **Right**  | 1     | The user's body extends to the right of the camera's field of view.                      |
| **Top**    | 4     | The user's body extends above the camera's field of view.                                |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EDC"></span>

See also  
========  

<span id="ID4EFC"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameEdges Enumeration
RLTitle : FrameEdges Enumeration
KeywordK : FrameEdges enumeration
KeywordK : WindowsPreview.Kinect.FrameEdges enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.FrameEdges
KeywordF : FrameEdges
KeywordF : WindowsPreview.Kinect.FrameEdges
KeywordA : T:WindowsPreview.Kinect.FrameEdges
AssetID : T:WindowsPreview.Kinect.FrameEdges
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.FrameEdges
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
