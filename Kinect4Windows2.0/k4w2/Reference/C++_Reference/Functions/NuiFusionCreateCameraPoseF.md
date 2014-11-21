NuiFusionCreateCameraPoseFinder  
===============================  

Creates a new [INuiFusionCameraPoseFinder](../Interfaces/INuiFusionCameraPoseFinder.md). <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionCreateCameraPoseFinder(  
         const NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS *pCameraPoseFinderParameters,  
         UINT *pRandomFeatureLocationAndThresholdSeed,  
         INuiFusionCameraPoseFinder **ppNuiFusionCameraPoseFinder  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EL"></span>
#### Parameters  

*pCameraPoseFinderParameters*    
Type: NUI\_FUSION\_CAMERA\_POSE\_FINDER\_PARAMETERS  
[in] The parameters to use to initialize the object.  

*pRandomFeatureLocationAndThresholdSeed*    
Type: UINT  
[in, optional] The number used to seed the random number generator used internally by the pose finder. If you wish to have reproduceable results between runs against the same camera pose finder data, set this to the same value for each run.  

*ppNuiFusionCameraPoseFinder*    
Type: INuiFusionCameraPoseFinder  
[out] Upon success, the new [INuiFusionCameraPoseFinder](../Interfaces/INuiFusionCameraPoseFinder.md).  

<span id="ID4ES"></span>
#### Return value  

Type: HRESULT FUSIONAPI  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NuiFusionCreateCameraPoseFinder
RLTitle : NuiFusionCreateCameraPoseFinder
KeywordK : NuiFusionCreateCameraPoseFinder
KeywordF : NuiFusionCreateCameraPoseFinder
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.NuiFusionCreateCameraPoseFinder(NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS,UINT,INuiFusionCameraPoseFinder@)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.NuiFusionCreateCameraPoseFinder(NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS,UINT,INuiFusionCameraPoseFinder@)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.NuiFusionCreateCameraPoseFinder(NUI_FUSION_CAMERA_POSE_FINDER_PARAMETERS,UINT,INuiFusionCameraPoseFinder@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.NuiFusionCreateCameraPoseFinder
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
