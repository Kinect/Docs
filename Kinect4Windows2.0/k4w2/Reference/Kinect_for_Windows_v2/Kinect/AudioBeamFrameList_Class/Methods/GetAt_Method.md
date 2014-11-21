AudioBeamFrameList.GetAt Method  
===============================  

Retrieves an audio beam frame at a specified index in the list. <span id="syntaxSection"></span>

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
<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>^ GetAt(  
         uint32 index  
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
<td align="left"><pre><code>public <a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>GetAt (  
         uint index  
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
<td align="left"><pre><code>var audioBeamFrame = audioBeamFrameList.getAt(index);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*index*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The index of the audio beam frame list.  

<span id="ID4EP"></span>
#### Return value  

Type: [AudioBeamFrame](../../AudioBeamFrame_Class.md)  
The audio beam frame at the specified index.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[AudioBeamFrameList Class](../../AudioBeamFrameList_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetAt Method
RLTitle : AudioBeamFrameList.GetAt Method
KeywordK : GetAt method
KeywordK : AudioBeamFrameList.GetAt method
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList.GetAt
KeywordF : AudioBeamFrameList.GetAt
KeywordF : GetAt
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList.GetAt(System.UInt32)
KeywordA : M:WindowsPreview.Kinect.AudioBeamFrameList.GetAt(System.UInt32)
AssetID : M:WindowsPreview.Kinect.AudioBeamFrameList.GetAt(System.UInt32)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameList.GetAt
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
