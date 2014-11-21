ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame Method  
===========================================================================  

Sets a reference depth frame that is used internally to help with tracking when calling the [AlignDepthFloatFrameToReconstruction](AlignDepthFloatFrameToReco.md) method to calculate a new camera pose.  
| ![](../../../../../../resources/note.gif)Note                                                         |
|-------------------------------------------------------------------------------------------------------|
| You should call this method only if you are not using the default tracking behavior of Kinect Fusion. |

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
void SetAlignDepthFloatToReconstructionReferenceFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ referenceFrame  
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
<td align="left"><pre><code>public void SetAlignDepthFloatToReconstructionReferenceFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>referenceFrame  
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
<td align="left"><pre><code>colorReconstruction.setAlignDepthFloatToReconstructionReferenceFrame(referenceFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Parameters  

*referenceFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
 A previously-created depth float frame that was successfully aligned, or a raycasted model depth.  

<span id="ID4ECB"></span>

Exceptions  
==========  

| Exception type                                                                                             | Condition                                                            |
|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| [ArgumentException](http://msdn.microsoft.com/en-us/library/system.argumentexception.aspx)                 | The *referenceDepthFloatFrame* parameter is an incorrect image size. |
| [ArgumentNullException](http://msdn.microsoft.com/en-us/library/system.argumentnullexception.aspx)         | The *referenceDepthFloatFrame* parameter is **null**.                |
| [InvalidOperationException](http://msdn.microsoft.com/en-us/library/system.invalidoperationexception.aspx) | The call failed for an unknown reason.                               |

<span id="remarks"></span>

Remarks  
=======  

Internally, the [AlignDepthFloatFrameToReconstruction](AlignDepthFloatFrameToReco.md) method saves the last depth frame that was passed to it and uses this image to help with tracking the next time that is called. For example, this can be used if you are reconstructing and lose track, and then want to restart tracking from a different known location without resetting the volume. To enable the tracking to succeed, you could perform a raycast from the new location to get a depth image (by calling the [CalculatePointCloudAndDepth](CalculatePointCloudAndDepth.md) method), and then call **SetAlignDepthFloatToReconstructionReferenceFrame** with the depth image before calling **AlignDepthFloatFrameToReconstruction**.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EPC"></span>

See also  
========  

<span id="ID4ERC"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SetAlignDepthFloatToReconstructionReferenceFrame Method
RLTitle : ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame Method
KeywordK : SetAlignDepthFloatToReconstructionReferenceFrame method
KeywordK : ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(Microsoft.Kinect.Fusion.DepthFloatFrame)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(Microsoft.Kinect.Fusion.DepthFloatFrame)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(Microsoft.Kinect.Fusion.DepthFloatFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame
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
