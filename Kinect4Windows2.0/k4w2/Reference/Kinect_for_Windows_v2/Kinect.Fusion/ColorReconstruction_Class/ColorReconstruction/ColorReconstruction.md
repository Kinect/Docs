ColorReconstruction Constructor (ReconstructionParameters, ReconstructionProcessingMode, Int32, Matrix4x4)  
==========================================================================================================  

Initializes a new instnce of the [ColorReconstruction](../../ColorReconstruction_Class.md) class. <span id="syntaxSection"></span>

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
ColorReconstruction(  
         <a href="../../ReconstructionParameters.md">ReconstructionParameters</a> parameters,  
         <a href="../../ReconstructionProcessingMode.md">ReconstructionProcessingMode</a> mode,  
         int32 deviceIndex,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> initialWorldToCameraTransform  
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
<td align="left"><pre><code>public ColorReconstruction (  
         <a href="../../ReconstructionParameters.md">ReconstructionParameters</a> parameters,  
         <a href="../../ReconstructionProcessingMode.md">ReconstructionProcessingMode</a> mode,  
         int deviceIndex,  
         <a href="../../Matrix4x4_Structure.md">Matrix4x4</a> initialWorldToCameraTransform  
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
<td align="left"><pre><code>var colorReconstruction = new Microsoft.Kinect.Fusion.ColorReconstruction(parameters, mode, deviceIndex, initialWorldToCameraTransform);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*parameters*    
Type: [ReconstructionParameters](../../ReconstructionParameters.md)  
The reconstruction parameters to use.  

*mode*    
Type: [ReconstructionProcessingMode](../../ReconstructionProcessingMode.md)  
The reconstruction processing mode to use.  

*deviceIndex*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The index of the reconstruction device to use.  

*initialWorldToCameraTransform*    
Type: [Matrix4x4](../../Matrix4x4_Structure.md)  
The initial world-to-camera transform.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4ETB"></span>

See also  
========  

<span id="ID4EVB"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ColorReconstruction Constructor (ReconstructionParameters, ReconstructionProcessingMode, Int32, Matrix4x4)
RLTitle : ColorReconstruction Constructor (ReconstructionParameters, ReconstructionProcessingMode, Int32, Matrix4x4)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.#ctor(Microsoft.Kinect.Fusion.ReconstructionParameters,Microsoft.Kinect.Fusion.ReconstructionProcessingMode,System.Int32,Microsoft.Kinect.Fusion.Matrix4x4)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.#ctor(Microsoft.Kinect.Fusion.ReconstructionParameters,Microsoft.Kinect.Fusion.ReconstructionProcessingMode,System.Int32,Microsoft.Kinect.Fusion.Matrix4x4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction
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
