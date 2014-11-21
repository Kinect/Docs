ColorReconstruction.SmoothDepthFloatFrame Method  
================================================  

Spatially smoothes a depth float image frame using edge-preserving filtering. <span id="syntaxSection"></span>

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
void SmoothDepthFloatFrame(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         uint32 kernelWidth,  
         float32 distanceThreshold,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ smoothDepthFloatFrame  
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
<td align="left"><pre><code>public void SmoothDepthFloatFrame (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         uint kernelWidth,  
         float distanceThreshold,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>smoothDepthFloatFrame  
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
<td align="left"><pre><code>colorReconstruction.smoothDepthFloatFrame(depthFloatFrame, kernelWidth, distanceThreshold, smoothDepthFloatFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
A source depth float frame.  

*kernelWidth*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The smoothing kernel width. The valid values are listed in the following table.  

| *kernelWidth value* | Smoothing kernel block size |
|---------------------|-----------------------------|
| 1                   | 3×3                         |
| 2                   | 5×5                         |
| 3                   | 7×7                         |

*distanceThreshold*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

The distance difference range that smoothing occurs in. Pixels with neighboring pixels outside this distance range will not be smoothed (larger values indicate discontinuity/edge). This value must be greater than zero.  

*smoothDepthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
A depth float frame that receives the smoothed depth frame.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E3C"></span>

See also  
========  

<span id="ID4E5C"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SmoothDepthFloatFrame Method
RLTitle : ColorReconstruction.SmoothDepthFloatFrame Method
KeywordK : SmoothDepthFloatFrame method
KeywordK : ColorReconstruction.SmoothDepthFloatFrame method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.SmoothDepthFloatFrame
KeywordF : ColorReconstruction.SmoothDepthFloatFrame
KeywordF : SmoothDepthFloatFrame
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.SmoothDepthFloatFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt32,System.Single,Microsoft.Kinect.Fusion.DepthFloatFrame)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.SmoothDepthFloatFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt32,System.Single,Microsoft.Kinect.Fusion.DepthFloatFrame)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.SmoothDepthFloatFrame(Microsoft.Kinect.Fusion.DepthFloatFrame,System.UInt32,System.Single,Microsoft.Kinect.Fusion.DepthFloatFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.SmoothDepthFloatFrame
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
