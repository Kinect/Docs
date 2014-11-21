AudioBeamFrameList.GetMany Method  
=================================  

Retrieves the audio beam frames that start at the specified index in the audio beam frame list. <span id="syntaxSection"></span>

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
uint32 GetMany(  
         uint32 startIndex,  
         out Array&lt;<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;^ items  
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
<td align="left"><pre><code>public uint GetMany (  
         uint startIndex,  
         out Array&lt;<a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;[] items  
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
<td align="left"><pre><code>var number = audioBeamFrameList.getMany(startIndex, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*startIndex*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The zero-based index of the start of the frames in the list.  

*items*    
Type: [AudioBeamFrame](../../AudioBeamFrame_Class.md)  
The frames that start at startIndex in the list.  

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: uint32  
Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
Type: Number  

The number of frames retrieved.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EGB"></span>

See also  
========  

<span id="ID4EIB"></span>
#### Reference  

[AudioBeamFrameList Class](../../AudioBeamFrameList_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetMany Method
RLTitle : AudioBeamFrameList.GetMany Method
KeywordK : GetMany method
KeywordK : AudioBeamFrameList.GetMany method
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList.GetMany
KeywordF : AudioBeamFrameList.GetMany
KeywordF : GetMany
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList.GetMany(System.UInt32,WindowsPreview.Kinect.AudioBeamFrame[]@)
KeywordA : M:WindowsPreview.Kinect.AudioBeamFrameList.GetMany(System.UInt32,WindowsPreview.Kinect.AudioBeamFrame[]@)
AssetID : M:WindowsPreview.Kinect.AudioBeamFrameList.GetMany(System.UInt32,WindowsPreview.Kinect.AudioBeamFrame[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameList.GetMany
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
