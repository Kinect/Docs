ColorFrame.CopyConvertedFrameDataToBuffer Method  
================================================  

Converts the raw format into the requested format and copies the data into the memory location provided. <span id="syntaxSection"></span>

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
void CopyConvertedFrameDataToBuffer(  
         IBuffer^ buffer,  
         <a href="../../ColorImageFormat.md">ColorImageFormat</a> colorFormat  
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
<td align="left"><pre><code>public void CopyConvertedFrameDataToBuffer (  
         IBufferbuffer,  
         <a href="../../ColorImageFormat.md">ColorImageFormat</a> colorFormat  
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
<td align="left"><pre><code>colorFrame.copyConvertedFrameDataToBuffer(buffer, colorFormat);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*buffer*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The buffer to fill.  

*colorFormat*    
Type: [ColorImageFormat](../../ColorImageFormat.md)  
The desired color image format.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ECB"></span>

See also  
========  

<span id="ID4EEB"></span>
#### Reference  

[ColorFrame Class](../../ColorFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyConvertedFrameDataToBuffer Method
RLTitle : ColorFrame.CopyConvertedFrameDataToBuffer Method
KeywordK : CopyConvertedFrameDataToBuffer method
KeywordK : ColorFrame.CopyConvertedFrameDataToBuffer method
KeywordF : WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToBuffer
KeywordF : ColorFrame.CopyConvertedFrameDataToBuffer
KeywordF : CopyConvertedFrameDataToBuffer
KeywordF : WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.ColorImageFormat)
KeywordA : M:WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.ColorImageFormat)
AssetID : M:WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToBuffer(Windows.Storage.Streams.IBuffer,WindowsPreview.Kinect.ColorImageFormat)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToBuffer
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
