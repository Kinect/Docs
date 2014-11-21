FaceFrameFeatures Enumeration  
=============================  

Flags that indicate the face frame features that are present. <span id="syntaxSection"></span>

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
public enum class FaceFrameFeatures</code></pre></td>
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
public enum FaceFrameFeatures</code></pre></td>
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
<td align="left"><pre><code>var faceFrameFeatures = Microsoft.Kinect.Face.FaceFrameFeatures.none;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EOC"></span>

Members  
=======  

| Member                         | Value | Description                                  |
|--------------------------------|-------|----------------------------------------------|
| **None**                       | 0     | No data is present.                          |
| **BoundingBoxInInfraredSpace** | 1     | Infrared space bounding box data is present. |
| **PointsInInfraredSpace**      | 2     | Infrared space data is present.              |
| **BoundingBoxInColorSpace**    | 4     | Color space bounding box data is present.    |
| **PointsInColorSpace**         | 8     | Color space point data is present.           |
| **RotationOrientation**        | 16    | Rotation orientation data is present.        |
| **Happy**                      | 32    | Happiness data is present.                   |
| **RightEyeClosed**             | 64    | Right eye data is present.                   |
| **LeftEyeClosed**              | 128   | Left eye data is present.                    |
| **MouthOpen**                  | 256   | Mouth open data is present.                  |
| **MouthMoved**                 | 512   | Mouth movement data is present.              |
| **LookingAway**                | 1024  | Looking away data is present.                |
| **Glasses**                    | 2048  | Glasses data is present.                     |
| **FaceEngagement**             | 4096  | Face engagement data is present.             |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EVC"></span>

See also  
========  

<span id="ID4EXC"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameFeatures Enumeration
RLTitle : FaceFrameFeatures Enumeration
KeywordK : FaceFrameFeatures enumeration
KeywordK : Microsoft.Kinect.Face.FaceFrameFeatures enumeration
HelpPriority : 2
KeywordF : Microsoft.Kinect.Face.FaceFrameFeatures
KeywordF : FaceFrameFeatures
KeywordF : Microsoft.Kinect.Face.FaceFrameFeatures
KeywordA : T:Microsoft.Kinect.Face.FaceFrameFeatures
AssetID : T:Microsoft.Kinect.Face.FaceFrameFeatures
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameFeatures
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
