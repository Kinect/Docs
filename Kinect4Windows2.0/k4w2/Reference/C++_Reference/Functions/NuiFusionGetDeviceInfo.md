NuiFusionGetDeviceInfo  
======================  

Provides information about a Kinect Fusion reconstruction processing device. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionGetDeviceInfo(  
         _NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE type,  
         INT index,  
         PWSTR pDescription,  
         UINT descriptionSizeInChars,  
         PWSTR pInstancePath,  
         UINT instancePathSizeInChars,  
         UINT *pMemoryKB  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*type*    
Type: \_NUI\_FUSION\_RECONSTRUCTION\_PROCESSOR\_TYPE  
[in] The reconstruction processing mode of the device.  

*index*    
Type: INT  
[in] The index of the device.  

*pDescription*    
Type: PWSTR  
 The description of the device.  

*descriptionSizeInChars*    
Type: UINT  
[in] The size of the description, in bytes.  

*pInstancePath*    
Type: PWSTR  
The DirectX instance path of the GPU being used for reconstruction.  

*instancePathSizeInChars*    
Type: UINT  
[in] The size of the instance path, in bytes.  

*pMemoryKB*    
Type: UINT  
[out, optional] Gets the amount of dedicated video memory on the GPU being used for reconstruction.  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT FUSIONAPI  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NuiFusionGetDeviceInfo
RLTitle : NuiFusionGetDeviceInfo
KeywordK : NuiFusionGetDeviceInfo
KeywordF : NuiFusionGetDeviceInfo
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo(_NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,PWSTR,UINT,PWSTR,UINT,UINT@)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo(_NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,PWSTR,UINT,PWSTR,UINT,UINT@)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo(_NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,PWSTR,UINT,PWSTR,UINT,UINT@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
