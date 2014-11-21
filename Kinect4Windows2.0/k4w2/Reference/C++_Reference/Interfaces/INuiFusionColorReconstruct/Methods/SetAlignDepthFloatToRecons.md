INuiFusionColorReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame Method  
======================================================================================  

Sets a reference depth frame that is used internally to help with tracking when calling the [AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md) method to calculate a new camera pose.  
| ![](../../../../../../resources/note.gif)Note                                                         |
|-------------------------------------------------------------------------------------------------------|
| You should call this method only if you are not using the default tracking behavior of Kinect Fusion. |

<span id="syntaxSection"></span>

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
HRESULT SetAlignDepthFloatToReconstructionReferenceFrame(  
         const NUI_FUSION_IMAGE_FRAME *pReferenceDepthFloatFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EN"></span>
#### Parameters  

*pReferenceDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
A previously-created depth float frame that was successfully aligned, or a raycasted model depth.  

<span id="ID4EW"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SetAlignDepthFloatToReconstructionReferenceFrame Method
RLTitle : INuiFusionColorReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame Method
KeywordK : SetAlignDepthFloatToReconstructionReferenceFrame method
KeywordK : INuiFusionColorReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame method
KeywordF : INuiFusionColorReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(NUI_FUSION_IMAGE_FRAME)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(NUI_FUSION_IMAGE_FRAME)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(NUI_FUSION_IMAGE_FRAME)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
