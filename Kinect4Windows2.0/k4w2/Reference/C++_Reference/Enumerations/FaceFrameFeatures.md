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
<td align="left"><pre><code>typedef enum _FaceFrameFeatures  
{  
    FaceFrameFeatures_None = 0,  
    FaceFrameFeatures_BoundingBoxInInfraredSpace = 0x1,  
    FaceFrameFeatures_PointsInInfraredSpace = 0x2,  
    FaceFrameFeatures_BoundingBoxInColorSpace = 0x4,  
    FaceFrameFeatures_PointsInColorSpace = 0x8,  
    FaceFrameFeatures_RotationOrientation = 0x10,  
    FaceFrameFeatures_Happy = 0x20,  
    FaceFrameFeatures_RightEyeClosed = 0x40,  
    FaceFrameFeatures_LeftEyeClosed = 0x80,  
    FaceFrameFeatures_MouthOpen = 0x100,  
    FaceFrameFeatures_MouthMoved = 0x200,  
    FaceFrameFeatures_LookingAway = 0x400,  
    FaceFrameFeatures_Glasses = 0x800,  
    FaceFrameFeatures_FaceEngagement = 0x1000  
} FaceFrameFeatures, FaceFrameFeatures_None, FaceFrameFeatures_BoundingBoxInInfraredSpace, FaceFrameFeatures_PointsInInfraredSpace, FaceFrameFeatures_BoundingBoxInColorSpace, FaceFrameFeatures_PointsInColorSpace, FaceFrameFeatures_RotationOrientation, FaceFrameFeatures_Happy, FaceFrameFeatures_RightEyeClosed, FaceFrameFeatures_LeftEyeClosed, FaceFrameFeatures_MouthOpen, FaceFrameFeatures_MouthMoved, FaceFrameFeatures_LookingAway, FaceFrameFeatures_Glasses, FaceFrameFeatures_FaceEngagement;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELC"></span>

Constants  
=========  

| Constant                                      | Description                                  |
|-----------------------------------------------|----------------------------------------------|
| FaceFrameFeatures\_None                       | No data is present.                          |
| FaceFrameFeatures\_BoundingBoxInInfraredSpace | Infrared space bounding box data is present. |
| FaceFrameFeatures\_PointsInInfraredSpace      | Infrared space data is present.              |
| FaceFrameFeatures\_BoundingBoxInColorSpace    | Color space bounding box data is present.    |
| FaceFrameFeatures\_PointsInColorSpace         | Color space point data is present.           |
| FaceFrameFeatures\_RotationOrientation        | Rotation orientation data is present.        |
| FaceFrameFeatures\_Happy                      | Happiness data is present.                   |
| FaceFrameFeatures\_RightEyeClosed             | Right eye data is present.                   |
| FaceFrameFeatures\_LeftEyeClosed              | Left eye data is present.                    |
| FaceFrameFeatures\_MouthOpen                  | Mouth open data is present.                  |
| FaceFrameFeatures\_MouthMoved                 | Mouth movement data is present.              |
| FaceFrameFeatures\_LookingAway                | Looking away data is present.                |
| FaceFrameFeatures\_Glasses                    | Glasses data is present.                     |
| FaceFrameFeatures\_FaceEngagement             | Face engagement data is present.             |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameFeatures Enumeration
RLTitle : FaceFrameFeatures Enumeration
KeywordK : FaceFrameFeatures enumeration
HelpPriority : 2
KeywordF : FaceFrameFeatures
KeywordF : Microsoft.Kinect.face.FaceFrameFeatures
KeywordA : T:Microsoft.Kinect.face.FaceFrameFeatures
AssetID : T:Microsoft.Kinect.face.FaceFrameFeatures
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FaceFrameFeatures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
