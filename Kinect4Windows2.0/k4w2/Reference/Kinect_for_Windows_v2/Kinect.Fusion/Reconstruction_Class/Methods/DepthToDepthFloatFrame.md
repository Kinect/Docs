Reconstruction.DepthToDepthFloatFrame Method  
============================================  

Converts the specified buffer of Kinect depth pixels to a [DepthFloatFrame](../../DepthFloatFrame_Class.md) object. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>reconstruction.depthToDepthFloatFrame(depthImageData, minDepthClip, maxDepthClip, mirrorDepth, depthFloatFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EO"></span>
#### Parameters  

*depthImageData*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
 The buffer of Kinect depth pixels in unsigned short format to convert. This data must have the same pixel resolution as the *depthFloatFrame* parameter.  

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

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4ENC"></span>

See also  
========  

<span id="ID4EPC"></span>
#### Reference  

[Reconstruction Class](../../Reconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DepthToDepthFloatFrame Method
RLTitle : Reconstruction.DepthToDepthFloatFrame Method
KeywordK : DepthToDepthFloatFrame method
KeywordK : Reconstruction.DepthToDepthFloatFrame method
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.DepthToDepthFloatFrame
KeywordF : Reconstruction.DepthToDepthFloatFrame
KeywordF : DepthToDepthFloatFrame
KeywordF : Microsoft.Kinect.Fusion.Reconstruction.DepthToDepthFloatFrame(Windows.Storage.Streams.IBuffer,System.Single,System.Single,System.Boolean,Microsoft.Kinect.Fusion.DepthFloatFrame)
KeywordA : M:Microsoft.Kinect.Fusion.Reconstruction.DepthToDepthFloatFrame(Windows.Storage.Streams.IBuffer,System.Single,System.Single,System.Boolean,Microsoft.Kinect.Fusion.DepthFloatFrame)
AssetID : M:Microsoft.Kinect.Fusion.Reconstruction.DepthToDepthFloatFrame(Windows.Storage.Streams.IBuffer,System.Single,System.Single,System.Boolean,Microsoft.Kinect.Fusion.DepthFloatFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.Reconstruction.DepthToDepthFloatFrame
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
