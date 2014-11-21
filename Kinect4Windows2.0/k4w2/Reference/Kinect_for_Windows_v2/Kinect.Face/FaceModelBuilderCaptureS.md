FaceModelBuilderCaptureStatus Enumeration  
=========================================  

Status of the face model builder capture. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public enum class FaceModelBuilderCaptureStatus</code></pre></td>
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
<td align="left"><pre><code>public enum FaceModelBuilderCaptureStatus</code></pre></td>
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
<td align="left"><pre><code>var faceModelBuilderCaptureStatus = Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus.faceTooFar;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EMB"></span>

Members  
=======  

| Member               | Value | Description                          |
|----------------------|-------|--------------------------------------|
| **FaceTooFar**       | 3     | The face is too far from the camera. |
| **FaceTooNear**      | 4     | The face is too near to the camera.  |
| **GoodFrameCapture** | 0     | The frame capture worked.            |
| **LostFaceTrack**    | 2     | The face is no longer tracked.       |
| **MovingTooFast**    | 5     | The face is moving too fast.         |
| **OtherViewsNeeded** | 1     | Other views are needed.              |
| **SystemError**      | 6     | A system error occured.              |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4ETB"></span>

See also  
========  

<span id="ID4EVB"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceModelBuilderCaptureStatus Enumeration
RLTitle : FaceModelBuilderCaptureStatus Enumeration
KeywordK : FaceModelBuilderCaptureStatus enumeration
KeywordK : Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus enumeration
HelpPriority : 2
KeywordF : Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus
KeywordF : FaceModelBuilderCaptureStatus
KeywordF : Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus
KeywordA : T:Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus
AssetID : T:Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModelBuilderCaptureStatus
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
