NUI\_FUSION\_CAMERA\_POSE\_FINDER\_PARAMETERS Structure  
=======================================================  

Defines the number of poses and feature sample locations used by the [INuiFusionCameraPoseFinder](../Interfaces/INuiFusionCameraPoseFinder.md) class. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS {  
    UINT featureSampleLocationsPerFrameCount;  
    UINT maxPoseHistoryCount;  
    FLOAT maxDepthThreshold;  
} NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EL"></span>
#### Members  

**featureSampleLocationsPerFrameCount**    
The number of features to extract per frame.  

**maxPoseHistoryCount**    
The maximum size of the camera pose finder pose history database.  

**maxDepthThreshold**    
The maximum depth to use when choosing a threshold value for each of the sample features in a key frame.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS Structure
RLTitle : NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS Structure
KeywordK : NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS structure
KeywordF : NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS
KeywordA : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS
AssetID : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
