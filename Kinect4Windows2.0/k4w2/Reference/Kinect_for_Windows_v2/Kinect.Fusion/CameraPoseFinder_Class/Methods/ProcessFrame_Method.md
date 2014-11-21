CameraPoseFinder.ProcessFrame Method  
====================================  

Adds the specified camera frame to the camera pose finder database if the frame differs enough from poses that already exist in the database. <span id="syntaxSection"></span>

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
<a href="../../CameraPoseFinderProcessRes.md">CameraPoseFinderProcessResult</a> ProcessFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>^ colorFrame,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform,  
         float32 minimumDistanceThreshold  
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
<td align="left"><pre><code>public <a href="../../CameraPoseFinderProcessRes.md">CameraPoseFinderProcessResult</a> ProcessFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>colorFrame,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> worldToCameraTransform,  
         float minimumDistanceThreshold  
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
<td align="left"><pre><code>var cameraPoseFinderProcessResult = cameraPoseFinder.processFrame(depthFloatFrame, colorFrame, worldToCameraTransform, minimumDistanceThreshold);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
 The depth float frame to be processed. This frame must have valid camera parameters and have a minimum size of 80×60. Also, this frame must be the same size and have been captured at the same time as the *colorFrame* parameter.  

*colorFrame*    
Type: [ColorImageFrame](../../ColorImageFrame_Class.md)  
 The color frame to be processed. This frame must have valid camera parameters and have a minimum size of 80×60. Also, this frame must be the same size and have been captured at the same time as the *depthFloatFrame* parameter.  

*worldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
 The current camera pose. This is usually the camera pose result from the most recent call to the [Reconstruction.AlignPointClouds](../../Reconstruction_Class/Methods/AlignPointClouds_Method.md) or [Reconstruction.AlignDepthFloatFrameToReconstruction](../../Reconstruction_Class/Methods/AlignDepthFloatFrameToReco.md) method.  

*minimumDistanceThreshold*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

Threshold in the range [0.0f, 1.0f] that specifies how different the *worldToCameraTransform* pose must be from the poses that are already stored in the database. Input frames that have a minimum distance equal to or above this threshold when compared to existing poses will be added to the database. Set this value to 0.0f to always add the pose to the database when this function is called. Note that setting this value to 0.0f can lead to many duplicated poses unless your application implements its own test.  

<span id="ID4EP"></span>
#### Return value  

Type: [CameraPoseFinderProcessResult](../../CameraPoseFinderProcessRes.md)  
The result of the operation.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EIC"></span>

See also  
========  

<span id="ID4EKC"></span>
#### Reference  

[CameraPoseFinder Class](../../CameraPoseFinder_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : CameraPoseFinder.ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : CameraPoseFinder.ProcessFrame method
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.ProcessFrame
KeywordF : CameraPoseFinder.ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.Matrix4x4,System.Single)
KeywordA : M:Microsoft.Kinect.Fusion.CameraPoseFinder.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.Matrix4x4,System.Single)
AssetID : M:Microsoft.Kinect.Fusion.CameraPoseFinder.ProcessFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame,Microsoft.Kinect.Fusion.Matrix4x4,System.Single)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinder.ProcessFrame
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
