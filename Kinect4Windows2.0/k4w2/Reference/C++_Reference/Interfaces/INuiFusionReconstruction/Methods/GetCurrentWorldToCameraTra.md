INuiFusionReconstruction::GetCurrentWorldToCameraTransform Method  
=================================================================  

Retrieves the current internal world-to-camera transform (camera view pose). <span id="syntaxSection"></span>

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
HRESULT GetCurrentWorldToCameraTransform(  
         Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pWorldToCameraTransform*    
Type: Matrix4  
The current world-to-camera pose.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetCurrentWorldToCameraTransform Method
RLTitle : INuiFusionReconstruction::GetCurrentWorldToCameraTransform Method
KeywordK : GetCurrentWorldToCameraTransform method
KeywordK : INuiFusionReconstruction::GetCurrentWorldToCameraTransform method
KeywordF : INuiFusionReconstruction::GetCurrentWorldToCameraTransform
KeywordF : GetCurrentWorldToCameraTransform
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.GetCurrentWorldToCameraTransform(Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.GetCurrentWorldToCameraTransform(Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.GetCurrentWorldToCameraTransform(Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::GetCurrentWorldToCameraTransform
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
