CameraIntrinsics Structure  
==========================  

Represents the calibration data for the depth camera. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _CameraIntrinsics {  
    float FocalLengthX;  
    float FocalLengthY;  
    float PrincipalPointX;  
    float PrincipalPointY;  
    float RadialDistortionSecondOrder;  
    float RadialDistortionFourthOrder;  
    float RadialDistortionSixthOrder;  
} CameraIntrinsics;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**FocalLengthX**    
The X focal length of the camera, in pixels.  

**FocalLengthY**    
The Y focal length of the camera, in pixels.  

**PrincipalPointX**    
The principal point of the camera in the X dimension, in pixels.  

**PrincipalPointY**    
The principal point of the camera in the Y dimension, in pixels.  

**RadialDistortionSecondOrder**    
The second order radial distortion parameter of the camera.  

**RadialDistortionFourthOrder**    
The fourth order radial distortion parameter of the camera.  

**RadialDistortionSixthOrder**    
The sixth order radial distortion parameter of the camera.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraIntrinsics Structure
RLTitle : CameraIntrinsics Structure
KeywordK : CameraIntrinsics structure
KeywordF : CameraIntrinsics
KeywordF : Microsoft.Kinect.kinect.CameraIntrinsics
KeywordA : T:Microsoft.Kinect.kinect.CameraIntrinsics
AssetID : T:Microsoft.Kinect.kinect.CameraIntrinsics
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.CameraIntrinsics
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
