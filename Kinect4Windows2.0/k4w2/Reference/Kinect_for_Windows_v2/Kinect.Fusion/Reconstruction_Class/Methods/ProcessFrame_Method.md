Reconstruction.ProcessFrame Method  
==================================  

A high-level function to process a depth frame through the Kinect Fusion pipeline.  
Specifically, this performs processing equivalent to the following functions for each frame:  

1.  AlignDepthFloatToReconstruction  
2.  IntegrateFrame  

Users may also optionally call the low-level functions individually, instead of calling this function, for more control. However, this function call will be faster due to the integrated nature of the calls. After this call completes, if a visible output image of the reconstruction is required, the user can call CalculatePointCloud and then ShadePointCloud. The maximum image resolution supported in this function is 640x480.  

If there is a tracking error in the AlignDepthFloatToReconstruction stage, no depth data integration will be performed, and the camera pose will remain unchanged.  

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
<a href="../../AlignmentResult_Class.md">AlignmentResult</a>^ ProcessFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         uint16 maxAlignIterationCount,  
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
<td align="left"><pre><code>public <a href="../../AlignmentResult_Class.md">AlignmentResult</a>ProcessFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         UInt16 maxAlignIterationCount,  
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
<td align="left"><pre><code>var alignmentResult = reconstruction.processFrame(depthFloatFrame, maxAlignIterationCount, maxIntegrationWeight, worldToCameraTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ET"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
The depth float frame to be processed.  

*maxAlignIterationCount*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

The maximum number of iterations of the align camera tracking algorithm to run. The minimum value is 1. Using only a small number of iterations will have a faster runtime, however, the algorithm may not converge to the correct transformation.  

*maxIntegrationWeight*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

A parameter to control the temporal smoothing of depth integration. Lower values have more noisy representations, but objects that move appear and disappear faster, so are suitable for more dynamic environments. Higher values integrate objects more slowly, but provides finer detail with less noise.  

*worldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The best guess of the latest camera pose (usually the camera pose result from the last process call).  

<span id="ID4E3"></span>
#### Return value  

Type: [AlignmentResult](../../AlignmentResult_Class.md)  
The result of the operation.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E6B"></span>

See also  
========  

<span id="ID4EBC"></span>
#### Reference  

[Reconstruction Class](../../Reconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : Reconstruction.ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : Reconstruction.ProcessFrame method
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.ProcessFrame
KeywordF : Reconstruction.ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt16,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.Reconstruction.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt16,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.Reconstruction.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt16,System.UInt16,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Reconstruction.ProcessFrame
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
