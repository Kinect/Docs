INuiFusionCameraPoseFinder::FindCameraPose Method  
=================================================  

Retrieves the poses in the camera pose finder database that are most similar to the current camera input. <span id="syntaxSection"></span>

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
HRESULT FindCameraPose(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         INuiFusionMatchCandidates **ppMatchCandidates  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
The depth float frame to be processed. This frame must have valid camera parameters. Also, this frame must be the same size and have been captured at the same time as the colorFrame parameter.  

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
The color frame to be processed. This frame must have valid camera parameters. Also, this frame must be the same size and have been captured at the same time as the depthFloatFrame parameter.  

*ppMatchCandidates*    
Type: INuiFusionMatchCandidates  
A MatchCandidates object that contains a set of matched frames and poses. These poses and similarity measurements are ordered in terms of decreasing similarity.  

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
TOCTitle : FindCameraPose Method
RLTitle : INuiFusionCameraPoseFinder::FindCameraPose Method
KeywordK : FindCameraPose method
KeywordK : INuiFusionCameraPoseFinder::FindCameraPose method
KeywordF : INuiFusionCameraPoseFinder::FindCameraPose
KeywordF : FindCameraPose
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.FindCameraPose(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,INuiFusionMatchCandidates)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.FindCameraPose(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,INuiFusionMatchCandidates)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.FindCameraPose(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,INuiFusionMatchCandidates)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder::FindCameraPose
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
