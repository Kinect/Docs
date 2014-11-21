HighDetailFacePoints Enumeration  
================================  

High-detail face points. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public enum class HighDetailFacePoints</code></pre></td>
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
<td align="left"><pre><code>public enum HighDetailFacePoints</code></pre></td>
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
<td align="left"><pre><code>var highDetailFacePoints = Microsoft.Kinect.Face.HighDetailFacePoints.chinCenter;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EBF"></span>

Members  
=======  

| Member                     | Value | Description                            |
|----------------------------|-------|----------------------------------------|
| **ChinCenter**             | 4     | Center of the chin.                    |
| **ForeheadCenter**         | 28    | Center of the forehead.                |
| **Leftcheekbone**          | 458   | Left cheek bone.                       |
| **LeftcheekCenter**        | 412   | Center of the left cheek.              |
| **LefteyebrowCenter**      | 222   | Center of the left eyebrow.            |
| **LefteyebrowInner**       | 346   | Inner left eyebrow.                    |
| **LefteyebrowOuter**       | 140   | Outer left eyebrow.                    |
| **LefteyeInnercorner**     | 210   | Inner corner of the left eye.          |
| **LefteyeMidbottom**       | 1104  | Middle of the bottom of the left eye.  |
| **LefteyeMidtop**          | 241   | Middle of the top of the left eye.     |
| **LefteyeOutercorner**     | 469   | Outer corner of the left eye.          |
| **LowerjawLeftend**        | 1307  | Left end of the lower jaw.             |
| **LowerjawRightend**       | 1327  | Right end of the lower jaw.            |
| **MouthLeftcorner**        | 91    | Left corner of the mouth.              |
| **MouthLowerlipMidbottom** | 8     | Middle of the bottom of the lower lip. |
| **MouthLowerlipMidtop**    | 10    | Middle of the top of the lower lip.    |
| **MouthRightcorner**       | 687   | Right corner of the mouth.             |
| **MouthUpperlipMidbottom** | 1072  | Middle of the bottom of the upper lip. |
| **MouthUpperlipMidtop**    | 19    | Middle of the top of the upper lip.    |
| **NoseBottom**             | 14    | Bottom of the nose.                    |
| **NoseBottomleft**         | 156   | Bottom left of the nose.               |
| **NoseBottomright**        | 783   | Bottom right of the nose.              |
| **NoseTip**                | 18    | Tip of the nose.                       |
| **NoseTop**                | 24    | Top of the nose.                       |
| **NoseTopleft**            | 151   | Top left of the nose.                  |
| **NoseTopright**           | 772   | Top right of the nose.                 |
| **Rightcheekbone**         | 674   | Right cheek bone.                      |
| **RightcheekCenter**       | 933   | Center of the right cheek.             |
| **RighteyebrowCenter**     | 849   | Center of the right eyeborw.           |
| **RighteyebrowInner**      | 803   | Inner right eyebrow.                   |
| **RighteyebrowOuter**      | 758   | Outer right eyebrow.                   |
| **RighteyeInnercorner**    | 843   | Inner corner of the right eye.         |
| **RighteyeMidbottom**      | 1090  | Middle of the bottom of the right eye. |
| **RighteyeMidtop**         | 731   | Middle of the top of the right eye.    |
| **RighteyeOutercorner**    | 1117  | Outer corner of the right eye.         |

<span id="remarks"></span>

Remarks  
=======  

You will must cast the enumeration value to an **int** to use it as an index for acessing the point from the collection of verticies. The following example illustrates this:  

    CameraSpacePoint leftOuterEye = faceVertices[(int)HighDetailFacePoints.LefteyeOutercorner];  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4ESF"></span>

See also  
========  

<span id="ID4EUF"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HighDetailFacePoints Enumeration
RLTitle : HighDetailFacePoints Enumeration
KeywordK : HighDetailFacePoints enumeration
KeywordK : Microsoft.Kinect.Face.HighDetailFacePoints enumeration
HelpPriority : 2
KeywordF : Microsoft.Kinect.Face.HighDetailFacePoints
KeywordF : HighDetailFacePoints
KeywordF : Microsoft.Kinect.Face.HighDetailFacePoints
KeywordA : T:Microsoft.Kinect.Face.HighDetailFacePoints
AssetID : T:Microsoft.Kinect.Face.HighDetailFacePoints
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDetailFacePoints
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
