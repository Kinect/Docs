HighDefinitionFaceFrameSource.FeedAndCalculateFrameData Method  
==============================================================  

TBD <span id="syntaxSection"></span>

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
void FeedAndCalculateFrameData(  
         <a href="../../../Kinect/Body_Class.md">Body</a>^ body,  
         IBuffer^ infraredFrameBuffer,  
         IBuffer^ colorFrameBuffer,  
         IBuffer^ depthFrameBuffer  
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
<td align="left"><pre><code>public void FeedAndCalculateFrameData (  
         <a href="../../../Kinect/Body_Class.md">Body</a>body,  
         IBufferinfraredFrameBuffer,  
         IBuffercolorFrameBuffer,  
         IBufferdepthFrameBuffer  
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
<td align="left"><pre><code>highDefinitionFaceFrameSource.feedAndCalculateFrameData(body, body, infraredFrameBuffer, colorFrameBuffer, depthFrameBuffer);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*body*    
Type: [Body](../../../Kinect/Body_Class.md)  
The body to use for the calculation.  

*infraredFrameBuffer*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The infrared frame buffer to use for the calculation.  

*colorFrameBuffer*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The color frame buffer to use for the calculation.  

*depthFrameBuffer*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The depth frame buffer to use for the calculation.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EWB"></span>

See also  
========  

<span id="ID4EYB"></span>
#### Reference  

[HighDefinitionFaceFrameSource Class](../../HighDefinitionFaceFrameSou.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FeedAndCalculateFrameData Method
RLTitle : HighDefinitionFaceFrameSource.FeedAndCalculateFrameData Method
KeywordK : FeedAndCalculateFrameData method
KeywordK : HighDefinitionFaceFrameSource.FeedAndCalculateFrameData method
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.FeedAndCalculateFrameData
KeywordF : HighDefinitionFaceFrameSource.FeedAndCalculateFrameData
KeywordF : FeedAndCalculateFrameData
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.FeedAndCalculateFrameData(WindowsPreview.Kinect.Body,Windows.Kinect.Body,Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer)
KeywordA : M:Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.FeedAndCalculateFrameData(WindowsPreview.Kinect.Body,Windows.Kinect.Body,Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer)
AssetID : M:Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.FeedAndCalculateFrameData(WindowsPreview.Kinect.Body,Windows.Kinect.Body,Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource.FeedAndCalculateFrameData
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
