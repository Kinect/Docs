AudioBeamSubFrame.CopyFrameDataToBuffer Method  
==============================================  

Copies the frame data into the array provided. <span id="syntaxSection"></span>

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
void CopyFrameDataToBuffer(  
         IBuffer^ buffer  
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
<td align="left"><pre><code>public void CopyFrameDataToBuffer (  
         IBufferbuffer  
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
<td align="left"><pre><code>audioBeamSubFrame.copyFrameDataToBuffer(buffer);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*buffer*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
 The array to fill.  

<span id="remarks"></span>

Remarks  
=======  

The frame data is a mono 32-bit IEEE floating point PCM stream sampled at 16 kHz. Typical PCM values will be between -1 and +1.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EBB"></span>

See also  
========  

<span id="ID4EDB"></span>
#### Reference  

[AudioBeamSubFrame Class](../../AudioBeamSubFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyFrameDataToBuffer Method
RLTitle : AudioBeamSubFrame.CopyFrameDataToBuffer Method
KeywordK : CopyFrameDataToBuffer method
KeywordK : AudioBeamSubFrame.CopyFrameDataToBuffer method
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame.CopyFrameDataToBuffer
KeywordF : AudioBeamSubFrame.CopyFrameDataToBuffer
KeywordF : CopyFrameDataToBuffer
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame.CopyFrameDataToBuffer(Windows.Storage.Streams.IBuffer)
KeywordA : M:WindowsPreview.Kinect.AudioBeamSubFrame.CopyFrameDataToBuffer(Windows.Storage.Streams.IBuffer)
AssetID : M:WindowsPreview.Kinect.AudioBeamSubFrame.CopyFrameDataToBuffer(Windows.Storage.Streams.IBuffer)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamSubFrame.CopyFrameDataToBuffer
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
