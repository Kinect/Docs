INuiFusionMatchCandidates::GetMatchPoses Method  
===============================================  

Gets a collection of the camera poses in the database that were match candidates to the input depth frame. <span id="syntaxSection"></span>

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
HRESULT GetMatchPoses(  
         const Matrix4 **pPoses  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pPoses*    
Type: Matrix4  
A collection of the camera poses in the database that were match candidates to the input depth frame.  

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
TOCTitle : GetMatchPoses Method
RLTitle : INuiFusionMatchCandidates::GetMatchPoses Method
KeywordK : GetMatchPoses method
KeywordK : INuiFusionMatchCandidates::GetMatchPoses method
KeywordF : INuiFusionMatchCandidates::GetMatchPoses
KeywordF : GetMatchPoses
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.GetMatchPoses(Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.GetMatchPoses(Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.GetMatchPoses(Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates::GetMatchPoses
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
