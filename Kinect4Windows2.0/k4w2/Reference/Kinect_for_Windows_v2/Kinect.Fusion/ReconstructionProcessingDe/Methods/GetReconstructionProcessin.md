ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo Method  
===============================================================================  

Gets the device information for the device with the specified index for the specified processing mode. <span id="syntaxSection"></span>

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
static <a href="../../ReconstructionProcessingDe.md">ReconstructionProcessingDeviceInfo</a>^ GetReconstructionProcessingDeviceInfo(  
         <a href="../../ReconstructionProcessingMode.md">ReconstructionProcessingMode</a> mode,  
         int32 index  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public static <a href="../../ReconstructionProcessingDe.md">ReconstructionProcessingDeviceInfo</a>GetReconstructionProcessingDeviceInfo (  
         <a href="../../ReconstructionProcessingMode.md">ReconstructionProcessingMode</a> mode,  
         int index  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var reconstructionProcessingDeviceInfo = Microsoft.Kinect.Fusion.ReconstructionProcessingDeviceInfo.getReconstructionProcessingDeviceInfo(mode, index);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*mode*    
Type: [ReconstructionProcessingMode](../../ReconstructionProcessingMode.md)  
The processing mode.  

*index*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The device index.  

<span id="ID4EQ"></span>
#### Return value  

Type: [ReconstructionProcessingDeviceInfo](../../ReconstructionProcessingDe.md)  
The device information.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[ReconstructionProcessingDeviceInfo Class](../../ReconstructionProcessingDe.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetReconstructionProcessingDeviceInfo Method
RLTitle : ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo Method
KeywordK : GetReconstructionProcessingDeviceInfo method
KeywordK : ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo method
KeywordF : Microsoft.Kinect.Fusion.ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo
KeywordF : ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo
KeywordF : GetReconstructionProcessingDeviceInfo
KeywordF : Microsoft.Kinect.Fusion.ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo(Microsoft.Kinect.Fusion.ReconstructionProcessingMode,System.Int32)
KeywordA : M:Microsoft.Kinect.Fusion.ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo(Microsoft.Kinect.Fusion.ReconstructionProcessingMode,System.Int32)
AssetID : M:Microsoft.Kinect.Fusion.ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo(Microsoft.Kinect.Fusion.ReconstructionProcessingMode,System.Int32)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ReconstructionProcessingDeviceInfo.GetReconstructionProcessingDeviceInfo
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
