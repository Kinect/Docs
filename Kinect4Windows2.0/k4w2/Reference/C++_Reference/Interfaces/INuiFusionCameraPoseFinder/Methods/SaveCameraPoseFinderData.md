INuiFusionCameraPoseFinder::SaveCameraPoseFinderDatabase Method  
===============================================================  

Saves the camera pose finder database to disk. <span id="syntaxSection"></span>

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
HRESULT SaveCameraPoseFinderDatabase(  
         LPCWSTR filename  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*filename*    
Type: LPCWSTR  
The filename of the database file to save to.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

If the database is saved to disk alongside the reconstruction volume, you can restart and update reconstruction and tracking by reloading both files and then running the camera pose finder.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SaveCameraPoseFinderDatabase Method
RLTitle : INuiFusionCameraPoseFinder::SaveCameraPoseFinderDatabase Method
KeywordK : SaveCameraPoseFinderDatabase method
KeywordK : INuiFusionCameraPoseFinder::SaveCameraPoseFinderDatabase method
KeywordF : INuiFusionCameraPoseFinder::SaveCameraPoseFinderDatabase
KeywordF : SaveCameraPoseFinderDatabase
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.SaveCameraPoseFinderDatabase(LPCWSTR)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.SaveCameraPoseFinderDatabase(LPCWSTR)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.SaveCameraPoseFinderDatabase(LPCWSTR)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder::SaveCameraPoseFinderDatabase
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
