ColorFrame.LockRawImageBuffer Method  
====================================  

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
IBuffer^ LockRawImageBuffer()</code></pre></td>
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
<td align="left"><pre><code>public IBufferLockRawImageBuffer ()</code></pre></td>
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
<td align="left"><pre><code>var iBuffer = colorFrame.lockRawImageBuffer();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
The buffer containing the raw image.  

<span id="remarks"></span>

Remarks  
=======  

When you are finished reading the data, unlock the buffer.  

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

[ColorFrame Class](../../ColorFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : LockRawImageBuffer Method
RLTitle : ColorFrame.LockRawImageBuffer Method
KeywordK : LockRawImageBuffer method
KeywordK : ColorFrame.LockRawImageBuffer method
KeywordF : WindowsPreview.Kinect.ColorFrame.LockRawImageBuffer
KeywordF : ColorFrame.LockRawImageBuffer
KeywordF : LockRawImageBuffer
KeywordF : WindowsPreview.Kinect.ColorFrame.LockRawImageBuffer
KeywordA : M:WindowsPreview.Kinect.ColorFrame.LockRawImageBuffer
AssetID : M:WindowsPreview.Kinect.ColorFrame.LockRawImageBuffer
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrame.LockRawImageBuffer
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
