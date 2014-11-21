ColorReconstruction.DepthToDepthFloatFrame Method  
=================================================  

Converts the specified array of Kinect depth pixels to a [DepthFloatFrame](../../DepthFloatFrame_Class.md) object. <span id="syntaxSection"></span>

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
void DepthToDepthFloatFrame(  
         IBuffer^ depthImageData,  
         float32 minDepthClip,  
         float32 maxDepthClip,  
         bool mirrorDepth,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame  
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
<td align="left"><pre><code>public void DepthToDepthFloatFrame (  
         IBufferdepthImageData,  
         float minDepthClip,  
         float maxDepthClip,  
         bool mirrorDepth,  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame  
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
<td align="left"><pre><code>colorReconstruction.depthToDepthFloatFrame(depthImageData, minDepthClip, maxDepthClip, mirrorDepth, depthFloatFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EO"></span>
#### Parameters  

*depthImageData*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
 The array of Kinect depth pixels in unsigned short format to convert. This data must have the same pixel resolution as the *depthFloatFrame* parameter.  

*minDepthClip*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

The minimum depth threshold, meters. Values below this threshold will be set to zero.  

*maxDepthClip*    
[C++] Type: float32  
  [C\#] Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
  [JavaScript] Type: Number  
   

The maximum depth threshold, in meters. Values above this threshold will be set to 1,000.  

*mirrorDepth*    
[C++] Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
  [C\#] Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
  [JavaScript] Type: Boolean  
   

Specify **true** to mirror the depth values. Specify **false** so the image appears correct if viewing the Kinect sensor from behind.  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
 A floating-point depth float frame that receives the converted depth data. This data must have the same pixel resolution as the *depthImageData* parameter.  

<span id="ID4EIC"></span>

Exceptions  
==========  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Exception type</th>
<th align="left">Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.argumentexception.aspx">ArgumentException</a></td>
<td align="left">One of the following occurred:  
<ul>
<li>The <em>depthImageData</em> or <em>depthFloatFrame</em> parameter is an incorrect image size.</li>
<li>The pixel resolutions of the <em>depthImageData</em> and <em>depthFloatFrame</em> parameter do not match.</li>
</ul></td>
</tr>
<tr class="even">
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.argumentnullexception.aspx">ArgumentNullException</a></td>
<td align="left">The <em>depthImageData</em> or <em>depthFloatFrame</em> parameter is <strong>null</strong>.</td>
</tr>
<tr class="odd">
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.invalidoperationexception.aspx">InvalidOperationException</a></td>
<td align="left">One of the following occurred:  
<ul>
<li>The Kinect Runtime could not be accessed.</li>
<li>The device is not connected.</li>
<li>The call failed for an unknown reason.</li>
</ul></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The *minDepthClip* and *maxDepthClip* parameters enable clipping of the input data; for example, these values help to isolate particular objects or surfaces to be reconstructed. In situations where the camera is static or does not move significantly, the *minDepthClip* parameter is important for reconstruction integration, as it enables any voxels closer to the camera along this ray to be culled instead of persisting (as would happen if the pixels were simply set to zero and ignored in processing). When reconstructing large real-world size volumes, the *maxDepthClip* parameter is important when the camera moves around, as any voxels in view which are farther from the sensor than this threshold will be removed.  

This method runs on the GPU.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EQE"></span>

See also  
========  

<span id="ID4ESE"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DepthToDepthFloatFrame Method
RLTitle : ColorReconstruction.DepthToDepthFloatFrame Method
KeywordK : DepthToDepthFloatFrame method
KeywordK : ColorReconstruction.DepthToDepthFloatFrame method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.DepthToDepthFloatFrame
KeywordF : ColorReconstruction.DepthToDepthFloatFrame
KeywordF : DepthToDepthFloatFrame
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.DepthToDepthFloatFrame(Windows.Storage.Streams.IBuffer,System.Single,System.Single,System.Boolean,Microsoft.Kinect.Fusion.DepthFloatFrame)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.DepthToDepthFloatFrame(Windows.Storage.Streams.IBuffer,System.Single,System.Single,System.Boolean,Microsoft.Kinect.Fusion.DepthFloatFrame)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.DepthToDepthFloatFrame(Windows.Storage.Streams.IBuffer,System.Single,System.Single,System.Boolean,Microsoft.Kinect.Fusion.DepthFloatFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.DepthToDepthFloatFrame
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
