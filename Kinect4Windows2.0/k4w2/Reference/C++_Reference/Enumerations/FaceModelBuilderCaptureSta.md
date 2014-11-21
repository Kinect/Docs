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
<td align="left"><pre><code>typedef enum _FaceModelBuilderCaptureStatus  
{  
    FaceModelBuilderCaptureStatus_GoodFrameCapture = 0,  
    FaceModelBuilderCaptureStatus_OtherViewsNeeded = 1,  
    FaceModelBuilderCaptureStatus_LostFaceTrack = 2,  
    FaceModelBuilderCaptureStatus_FaceTooFar = 3,  
    FaceModelBuilderCaptureStatus_FaceTooNear = 4,  
    FaceModelBuilderCaptureStatus_MovingTooFast = 5,  
    FaceModelBuilderCaptureStatus_SystemError = 6  
} FaceModelBuilderCaptureStatus, FaceModelBuilderCaptureStatus_GoodFrameCapture, FaceModelBuilderCaptureStatus_OtherViewsNeeded, FaceModelBuilderCaptureStatus_LostFaceTrack, FaceModelBuilderCaptureStatus_FaceTooFar, FaceModelBuilderCaptureStatus_FaceTooNear, FaceModelBuilderCaptureStatus_MovingTooFast, FaceModelBuilderCaptureStatus_SystemError;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EPB"></span>

Constants  
=========  

| Constant                                        | Description                          |
|-------------------------------------------------|--------------------------------------|
| FaceModelBuilderCaptureStatus\_GoodFrameCapture | The frame capture worked.            |
| FaceModelBuilderCaptureStatus\_OtherViewsNeeded | Other views are needed.              |
| FaceModelBuilderCaptureStatus\_LostFaceTrack    | The face is no longer tracked.       |
| FaceModelBuilderCaptureStatus\_FaceTooFar       | The face is too far from the camera. |
| FaceModelBuilderCaptureStatus\_FaceTooNear      | The face is too near to the camera.  |
| FaceModelBuilderCaptureStatus\_MovingTooFast    | The face is moving too fast.         |
| FaceModelBuilderCaptureStatus\_SystemError      | A system error occured.              |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceModelBuilderCaptureStatus Enumeration
RLTitle : FaceModelBuilderCaptureStatus Enumeration
KeywordK : FaceModelBuilderCaptureStatus enumeration
HelpPriority : 2
KeywordF : FaceModelBuilderCaptureStatus
KeywordF : Microsoft.Kinect.face.FaceModelBuilderCaptureStatus
KeywordA : T:Microsoft.Kinect.face.FaceModelBuilderCaptureStatus
AssetID : T:Microsoft.Kinect.face.FaceModelBuilderCaptureStatus
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FaceModelBuilderCaptureStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
