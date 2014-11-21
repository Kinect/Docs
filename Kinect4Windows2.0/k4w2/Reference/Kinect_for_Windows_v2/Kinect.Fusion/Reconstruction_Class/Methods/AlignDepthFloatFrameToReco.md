Reconstruction.AlignDepthFloatFrameToReconstruction Method  
==========================================================  

Aligns a depth float image to the reconstruction volume to calculate the new camera pose. <span id="syntaxSection"></span>

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
<a href="../../AlignmentResult_Class.md">AlignmentResult</a>^ AlignDepthFloatFrameToReconstruction(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         int32 maxAlignIterationCount,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ deltaFromReferenceFrame  
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
<td align="left"><pre><code>public <a href="../../AlignmentResult_Class.md">AlignmentResult</a>AlignDepthFloatFrameToReconstruction (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         int maxAlignIterationCount,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>deltaFromReferenceFrame  
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
<td align="left"><pre><code>var alignmentResult = reconstruction.alignDepthFloatFrameToReconstruction(depthFloatFrame, maxAlignIterationCount, worldToCameraTransform, deltaFromReferenceFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
The depth float frame to be processed.  

*maxAlignIterationCount*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The maximum number of iterations of the algorithm to run. The minimum value is one. Using only a small number of iterations will have a faster run time, but the algorithm may not converge to the correct transformation.  

*worldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The best guess at the current camera pose. This is usually the camera pose result from the most recent call to the [Reconstruction.AlignPointClouds](AlignPointClouds_Method.md) or [ColorReconstruction.AlignDepthFloatFrameToReconstruction](../../ColorReconstruction_Class/Methods/AlignDepthFloatFrameToReco.md) method.  

*deltaFromReferenceFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  

A pre-allocated float image frame, to be filled with information about how well each observed pixel aligns with the passed-in reference frame. This could be processed to create a color rendering, or could be used as input to additional vision algorithms such as object segmentation. These residual values are normalized −1 to 1 and represent the alignment cost/energy for each pixel. Larger magnitude values (either positive or negative) represent more discrepancy, and lower values represent less discrepancy or less information at that pixel.  

Note that if valid depth exists, but no reconstruction model exists behind the depth pixels, a value of zero (which indicates perfect alignment) will be returned for that area. In contrast, where no valid depth occurs a value of one will always be returned. Pass **null** to this parameter if you do not want to use this functionality.  

<span id="ID4EP"></span>
#### Return value  

Type: [AlignmentResult](../../AlignmentResult_Class.md)  
The result of the operation.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EGC"></span>

See also  
========  

<span id="ID4EIC"></span>
#### Reference  

[Reconstruction Class](../../Reconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AlignDepthFloatFrameToReconstruction Method
RLTitle : Reconstruction.AlignDepthFloatFrameToReconstruction Method
KeywordK : AlignDepthFloatFrameToReconstruction method
KeywordK : Reconstruction.AlignDepthFloatFrameToReconstruction method
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.AlignDepthFloatFrameToReconstruction
KeywordF : Reconstruction.AlignDepthFloatFrameToReconstruction
KeywordF : AlignDepthFloatFrameToReconstruction
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.AlignDepthFloatFrameToReconstruction(Microsoft.Kinect.Fusion.DepthFloatFrame,System.Int32,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.DepthFloatFrame)
KeywordA : M:Microsoft.Kinect.Fusion.Reconstruction.AlignDepthFloatFrameToReconstruction(Microsoft.Kinect.Fusion.DepthFloatFrame,System.Int32,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.DepthFloatFrame)
AssetID : M:Microsoft.Kinect.Fusion.Reconstruction.AlignDepthFloatFrameToReconstruction(Microsoft.Kinect.Fusion.DepthFloatFrame,System.Int32,Microsoft.Kinect.Fusion.Matrix4x4,Microsoft.Kinect.Fusion.DepthFloatFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Reconstruction.AlignDepthFloatFrameToReconstruction
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
