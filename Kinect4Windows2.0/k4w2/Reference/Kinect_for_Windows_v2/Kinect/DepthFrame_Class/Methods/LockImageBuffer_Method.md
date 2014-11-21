DepthFrame.LockImageBuffer Method  
=================================  

Gives an app access to the underlying buffer used by the system to store this frame's data. <span id="syntaxSection"></span>

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
IBuffer^ LockImageBuffer()</code></pre></td>
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
<td align="left"><pre><code>public IBufferLockImageBuffer ()</code></pre></td>
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
<td align="left"><pre><code>var iBuffer = depthFrame.lockImageBuffer();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The underlying buffer used by the system to store this frame's data.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E1"></span>

See also  
========  

<span id="ID4E3"></span>
#### Reference  

[DepthFrame Class](../../DepthFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : LockImageBuffer Method
RLTitle : DepthFrame.LockImageBuffer Method
KeywordK : LockImageBuffer method
KeywordK : DepthFrame.LockImageBuffer method
KeywordF : WindowsPreview.Kinect.DepthFrame.LockImageBuffer
KeywordF : DepthFrame.LockImageBuffer
KeywordF : LockImageBuffer
KeywordF : WindowsPreview.Kinect.DepthFrame.LockImageBuffer
KeywordA : M:WindowsPreview.Kinect.DepthFrame.LockImageBuffer
AssetID : M:WindowsPreview.Kinect.DepthFrame.LockImageBuffer
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.DepthFrame.LockImageBuffer
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
