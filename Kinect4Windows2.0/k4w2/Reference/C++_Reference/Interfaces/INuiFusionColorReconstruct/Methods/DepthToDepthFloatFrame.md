INuiFusionColorReconstruction::DepthToDepthFloatFrame Method  
============================================================  

Converts the specified array of Kinect depth pixels to a NUI\_FUSION\_IMAGE\_FRAME object representing a depth float frame. <span id="syntaxSection"></span>

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
HRESULT DepthToDepthFloatFrame(  
         const UINT16 *pDepthImageData,  
         UINT countDepthImageDataBytes,  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         FLOAT minDepthClip,  
         FLOAT maxDepthClip,  
         BOOL mirrorDepth  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthImageData*    
Type: UINT16  
The array of Kinect depth pixels in unsigned short format to convert. This data must have the same pixel resolution as the pDepthFloatFrame parameter.  

*countDepthImageDataBytes*    
Type: UINT  
The size of the depth image, in bytes.  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
A floating-point depth float frame that receives the converted depth data. This data must have the same pixel resolution as the pDepthImageData parameter.  

*minDepthClip*    
Type: FLOAT  
The minimum depth threshold, meters. Values below this threshold will be set to zero.  

*maxDepthClip*    
Type: FLOAT  
The maximum depth threshold, in meters. Values above this threshold will be set to 1,000.  

*mirrorDepth*    
Type: BOOL  
Specify true to mirror the depth values. Specify false so the image appears correct if viewing the Kinect sensor from behind.  

<span id="ID4EP"></span>
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
TOCTitle : DepthToDepthFloatFrame Method
RLTitle : INuiFusionColorReconstruction::DepthToDepthFloatFrame Method
KeywordK : DepthToDepthFloatFrame method
KeywordK : INuiFusionColorReconstruction::DepthToDepthFloatFrame method
KeywordF : INuiFusionColorReconstruction::DepthToDepthFloatFrame
KeywordF : DepthToDepthFloatFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.DepthToDepthFloatFrame(UINT16,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.DepthToDepthFloatFrame(UINT16,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.DepthToDepthFloatFrame(UINT16,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::DepthToDepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
