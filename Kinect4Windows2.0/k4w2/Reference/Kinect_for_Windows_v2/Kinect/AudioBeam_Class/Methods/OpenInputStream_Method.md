AudioBeam.OpenInputStream Method  
================================  

Opens the input stream. The input stream is a mono 32-bit IEEE floating point PCM stream sampled at 16 kHz. Typical PCM values will be between -1 and +1. <span id="syntaxSection"></span>

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
IInputStream^ OpenInputStream()</code></pre></td>
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
<td align="left"><pre><code>public IInputStreamOpenInputStream ()</code></pre></td>
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
<td align="left"><pre><code>var iInputStream = audioBeam.openInputStream();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [IInputStream](http://msdn.microsoft.com/en-us/library/windows.storage.streams.iinputstream.aspx)  
The input stream.  

<span id="remarks"></span>

Remarks  
=======  

The input stream is a mono 32-bit IEEE floating point PCM stream sampled at 16 kHz. Typical PCM values will be between -1 and +1.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[AudioBeam Class](../../AudioBeam_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenInputStream Method
RLTitle : AudioBeam.OpenInputStream Method
KeywordK : OpenInputStream method
KeywordK : AudioBeam.OpenInputStream method
KeywordF : WindowsPreview.Kinect.AudioBeam.OpenInputStream
KeywordF : AudioBeam.OpenInputStream
KeywordF : OpenInputStream
KeywordF : WindowsPreview.Kinect.AudioBeam.OpenInputStream
KeywordA : M:WindowsPreview.Kinect.AudioBeam.OpenInputStream
AssetID : M:WindowsPreview.Kinect.AudioBeam.OpenInputStream
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeam.OpenInputStream
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
