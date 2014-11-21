NUI\_FUSION\_CAMERA\_PARAMETERS Structure  
=========================================  

Stores the intrinsic camera parameters. These parameters describe the optical system of the camera lens and sensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _NUI_FUSION_CAMERA_PARAMETERS {  
    FLOAT focalLengthX;  
    FLOAT focalLengthY;  
    FLOAT principalPointX;  
    FLOAT principalPointY;  
} NUI_FUSION_CAMERA_PARAMETERS;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**focalLengthX**    
The focal length for X normalized by the camera width.  

**focalLengthY**    
The focal length for Y normalized by the camera height.  

**principalPointX**    
The principal point for X normalized by the camera width.  

**principalPointY**    
The principal point for Y normalized by the camera height.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NUI_FUSION_CAMERA_PARAMETERS Structure
RLTitle : NUI_FUSION_CAMERA_PARAMETERS Structure
KeywordK : NUI_FUSION_CAMERA_PARAMETERS structure
KeywordF : NUI_FUSION_CAMERA_PARAMETERS
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_CAMERA_PARAMETERS
KeywordA : T:Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_CAMERA_PARAMETERS
AssetID : T:Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_CAMERA_PARAMETERS
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_CAMERA_PARAMETERS
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
