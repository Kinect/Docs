INuiFusionCameraPoseFinder::ProcessFrame Method  
===============================================  

Adds the specified camera frame to the camera pose finder database if the frame differs enough from poses that already exist in the database. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
HRESULT ProcessFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         const Matrix4 *pWorldToCameraTransform,  
         FLOAT minimumDistanceThreshold,  
         BOOL *pAddedPose,  
         BOOL *pHistoryTrimmed  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
 The depth float frame to be processed. This frame must have valid camera parameters and have a minimum size of 80×60. Also, this frame must be the same size and have been captured at the same time as the colorFrame parameter.  

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
 The color frame to be processed. This frame must have valid camera parameters and have a minimum size of 80×60. Also, this frame must be the same size and have been captured at the same time as the depthFloatFrame parameter.  

*pWorldToCameraTransform*    
Type: Matrix4  
The current camera pose. This is usually the camera pose result from the most recent call to the AlignPointClouds or AlignDepthFloatToReconstruction method.  

*minimumDistanceThreshold*    
Type: FLOAT  
Threshold in the range [0.0f, 1.0f] that specifies how different the worldToCameraTransform pose must be from the poses that are already stored in the database. Input frames that have a minimum distance equal to or above this threshold when compared to existing poses will be added to the database. Set this value to 0.0f to always add the pose to the database when this function is called. Note that setting this value to 0.0f can lead to many duplicated poses unless your application implements its own test.  

*pAddedPose*    
Type: BOOL  
A value indicating whether a new frame was added to the camera pose data.  

*pHistoryTrimmed*    
Type: BOOL  
A value indicating wether the camera pose finder removed frames from the frame history for performance reasons.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : INuiFusionCameraPoseFinder::ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : INuiFusionCameraPoseFinder::ProcessFrame method
KeywordF : INuiFusionCameraPoseFinder::ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4,FLOAT,BOOL,BOOL)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4,FLOAT,BOOL,BOOL)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4,FLOAT,BOOL,BOOL)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder::ProcessFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
