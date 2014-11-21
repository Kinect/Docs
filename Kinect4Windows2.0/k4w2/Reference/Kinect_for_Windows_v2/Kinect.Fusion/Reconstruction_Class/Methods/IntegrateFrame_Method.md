Reconstruction.IntegrateFrame Method  
====================================  

Integrates depth float data into the reconstruction volume from the passed camera pose.  
Note: this function will also set the internal camera pose.  

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
void IntegrateFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         uint16 maxIntegrationWeight,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform  
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
<td align="left"><pre><code>public void IntegrateFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         UInt16 maxIntegrationWeight,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform  
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
<td align="left"><pre><code>reconstruction.integrateFrame(depthFloatFrame, maxIntegrationWeight, worldToCameraTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EI"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
The depth float frame to be integrated.  

*maxIntegrationWeight*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

A parameter to control the temporal smoothing of depth integration. Minimum value is 1. Lower values have more noisy representations, but objects that move integrate and disintegrate faster, so are suitable for more dynamic environments. Higher values integrate objects more slowly, but provides finer detail with less noise.  

*worldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The camera pose (usually the camera pose result from the last AlignPointClouds or AlignDepthFloatToReconstruction).  

This method raises the following exceptions:  

|---------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Exception**             | **Raised By**                                                                                                               |
| ArgumentNullException     | Thrown when the *depthFloatFrame* parameter is null.                                                                        |
| ArgumentException         | Thrown when the *maxIntegrationWeight* parameter is less than 1 or greater than the maximum unsigned short value.           |
| InvalidOperationException | Thrown when the Kinect Runtime could not be accessed, the device is not connected or the call failed for an unknown reason. |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EXC"></span>

See also  
========  

<span id="ID4EZC"></span>
#### Reference  

[Reconstruction Class](../../Reconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IntegrateFrame Method
RLTitle : Reconstruction.IntegrateFrame Method
KeywordK : IntegrateFrame method
KeywordK : Reconstruction.IntegrateFrame method
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.IntegrateFrame
KeywordF : Reconstruction.IntegrateFrame
KeywordF : IntegrateFrame
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.IntegrateFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.Reconstruction.IntegrateFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.Reconstruction.IntegrateFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Reconstruction.IntegrateFrame
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
