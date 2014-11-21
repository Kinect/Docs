AudioBeamFrameReference.AcquireBeamFrames Method  
================================================  

Container for one frame's worth of audio beam image data. Can return null if the data is not available. Upon success, returns the AudioBeamFrame collection corresponding to this event, which must be Disposed. <span id="syntaxSection"></span>

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
IVectorView&lt;<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;^ AcquireBeamFrames()</code></pre></td>
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
<td align="left"><pre><code>public IReadOnlyList&lt;<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;AcquireBeamFrames ()</code></pre></td>
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
<td align="left"><pre><code>var iVectorView = audioBeamFrameReference.acquireBeamFrames();</code></pre></td>
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

One frame of audio beam image data.  

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

[AudioBeamFrameReference Class](../../AudioBeamFrameReference.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AcquireBeamFrames Method
RLTitle : AudioBeamFrameReference.AcquireBeamFrames Method
KeywordK : AcquireBeamFrames method
KeywordK : AudioBeamFrameReference.AcquireBeamFrames method
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReference.AcquireBeamFrames
KeywordF : AudioBeamFrameReference.AcquireBeamFrames
KeywordF : AcquireBeamFrames
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReference.AcquireBeamFrames
KeywordA : M:WindowsPreview.Kinect.AudioBeamFrameReference.AcquireBeamFrames
AssetID : M:WindowsPreview.Kinect.AudioBeamFrameReference.AcquireBeamFrames
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameReference.AcquireBeamFrames
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
