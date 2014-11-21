FaceModelBuilderCollectionStatus Enumeration  
============================================  

Status of the face model builder collection. <span id="syntaxSection"></span>

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
public enum class FaceModelBuilderCollectionStatus</code></pre></td>
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
public enum FaceModelBuilderCollectionStatus</code></pre></td>
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
<td align="left"><pre><code>var faceModelBuilderCollectionStatus = Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus.complete;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EOB"></span>

Members  
=======  

| Member                    | Value | Description                                |
|---------------------------|-------|--------------------------------------------|
| **Complete**              | 0     | The collection is complete.                |
| **FrontViewFramesNeeded** | 2     | Frames from the front view are needed.     |
| **LeftViewsNeeded**       | 4     | Frames from the left view are needed.      |
| **MoreFramesNeeded**      | 1     | More frames are needed.                    |
| **RightViewsNeeded**      | 8     | Frames from the right view are needed.     |
| **TiltedUpViewsNeeded**   | 16    | Frames from the tilted up view are needed. |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EVB"></span>

See also  
========  

<span id="ID4EXB"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceModelBuilderCollectionStatus Enumeration
RLTitle : FaceModelBuilderCollectionStatus Enumeration
KeywordK : FaceModelBuilderCollectionStatus enumeration
KeywordK : Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus enumeration
HelpPriority : 2
KeywordF : Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus
KeywordF : FaceModelBuilderCollectionStatus
KeywordF : Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus
KeywordA : T:Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus
AssetID : T:Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModelBuilderCollectionStatus
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
