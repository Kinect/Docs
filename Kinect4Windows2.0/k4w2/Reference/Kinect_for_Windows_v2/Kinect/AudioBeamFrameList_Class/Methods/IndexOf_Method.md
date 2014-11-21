AudioBeamFrameList.IndexOf Method  
=================================  

Retrieves the zero-based index of the first occurrence of the specified audio beam frame in the audio beam frame list. <span id="syntaxSection"></span>

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
bool IndexOf(  
         <a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>^ value,  
         out uint32 index  
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
<td align="left"><pre><code>public bool IndexOf (  
         <a href="../../AudioBeamFrame_Class.md">AudioBeamFrame</a>value,  
         out uint index  
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
<td align="left"><pre><code>var boolean = audioBeamFrameList.indexOf(value, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: [AudioBeamFrame](../../AudioBeamFrame_Class.md)  
The audio beam frame to find in the list.  

*index*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

If the item is found, this is the zero-based index of the item; otherwise, this parameter is 0.  

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
Type: Boolean  

True if the item is found; otherwise, false.  

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
TOCTitle : IndexOf Method
RLTitle : AudioBeamFrameList.IndexOf Method
KeywordK : IndexOf method
KeywordK : AudioBeamFrameList.IndexOf method
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList.IndexOf
KeywordF : AudioBeamFrameList.IndexOf
KeywordF : IndexOf
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList.IndexOf(WindowsPreview.Kinect.AudioBeamFrame,System.UInt32@)
KeywordA : M:WindowsPreview.Kinect.AudioBeamFrameList.IndexOf(WindowsPreview.Kinect.AudioBeamFrame,System.UInt32@)
AssetID : M:WindowsPreview.Kinect.AudioBeamFrameList.IndexOf(WindowsPreview.Kinect.AudioBeamFrame,System.UInt32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameList.IndexOf
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
