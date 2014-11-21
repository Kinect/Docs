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
<td align="left"><pre><code>typedef enum _FaceModelBuilderCollectionStatus  
{  
    FaceModelBuilderCollectionStatus_Complete = 0,  
    FaceModelBuilderCollectionStatus_MoreFramesNeeded = 0x1,  
    FaceModelBuilderCollectionStatus_FrontViewFramesNeeded = 0x2,  
    FaceModelBuilderCollectionStatus_LeftViewsNeeded = 0x4,  
    FaceModelBuilderCollectionStatus_RightViewsNeeded = 0x8,  
    FaceModelBuilderCollectionStatus_TiltedUpViewsNeeded = 0x10  
} FaceModelBuilderCollectionStatus, FaceModelBuilderCollectionStatus_Complete, FaceModelBuilderCollectionStatus_MoreFramesNeeded, FaceModelBuilderCollectionStatus_FrontViewFramesNeeded, FaceModelBuilderCollectionStatus_LeftViewsNeeded, FaceModelBuilderCollectionStatus_RightViewsNeeded, FaceModelBuilderCollectionStatus_TiltedUpViewsNeeded;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELB"></span>

Constants  
=========  

| Constant                                                | Description                                |
|---------------------------------------------------------|--------------------------------------------|
| FaceModelBuilderCollectionStatus\_Complete              | The collection is complete.                |
| FaceModelBuilderCollectionStatus\_MoreFramesNeeded      | More frames are needed.                    |
| FaceModelBuilderCollectionStatus\_FrontViewFramesNeeded | Frames from the front view are needed.     |
| FaceModelBuilderCollectionStatus\_LeftViewsNeeded       | Frames from the left view are needed.      |
| FaceModelBuilderCollectionStatus\_RightViewsNeeded      | Frames from the right view are needed.     |
| FaceModelBuilderCollectionStatus\_TiltedUpViewsNeeded   | Frames from the tilted up view are needed. |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceModelBuilderCollectionStatus Enumeration
RLTitle : FaceModelBuilderCollectionStatus Enumeration
KeywordK : FaceModelBuilderCollectionStatus enumeration
HelpPriority : 2
KeywordF : FaceModelBuilderCollectionStatus
KeywordF : Microsoft.Kinect.face.FaceModelBuilderCollectionStatus
KeywordA : T:Microsoft.Kinect.face.FaceModelBuilderCollectionStatus
AssetID : T:Microsoft.Kinect.face.FaceModelBuilderCollectionStatus
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FaceModelBuilderCollectionStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
