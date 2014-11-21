AudioBeamFrameReader.AcquireLatestBeamFrames Method  
===================================================  

Gets the latest audio beam frames. <span id="syntaxSection"></span>

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
IVectorView&lt;<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;^ AcquireLatestBeamFrames()</code></pre></td>
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
<td align="left"><pre><code>public IReadOnlyList&lt;<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;AcquireLatestBeamFrames ()</code></pre></td>
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
<td align="left"><pre><code>var iVectorView = audioBeamFrameReader.acquireLatestBeamFrames();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[AudioBeamFrame](../../AudioBeamFrame_Class.md)\>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[AudioBeamFrame](../../AudioBeamFrame_Class.md)\>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[AudioBeamFrame](../../AudioBeamFrame_Class.md)\>

The latest audio beam frames.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[AudioBeamFrameReader Class](../../AudioBeamFrameReader_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AcquireLatestBeamFrames Method
RLTitle : AudioBeamFrameReader.AcquireLatestBeamFrames Method
KeywordK : AcquireLatestBeamFrames method
KeywordK : AudioBeamFrameReader.AcquireLatestBeamFrames method
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader.AcquireLatestBeamFrames
KeywordF : AudioBeamFrameReader.AcquireLatestBeamFrames
KeywordF : AcquireLatestBeamFrames
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader.AcquireLatestBeamFrames
KeywordA : M:WindowsPreview.Kinect.AudioBeamFrameReader.AcquireLatestBeamFrames
AssetID : M:WindowsPreview.Kinect.AudioBeamFrameReader.AcquireLatestBeamFrames
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameReader.AcquireLatestBeamFrames
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
