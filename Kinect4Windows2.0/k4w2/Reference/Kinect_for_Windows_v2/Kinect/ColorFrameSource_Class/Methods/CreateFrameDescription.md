ColorFrameSource.CreateFrameDescription Method  
==============================================  

Creates a FrameDescription object for the ColorFrame of the requested format. <span id="syntaxSection"></span>

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
<a href="../../FrameDescription_Class.md">FrameDescription</a>^ CreateFrameDescription(  
         <a href="../../ColorImageFormat_Enumeration.md">ColorImageFormat</a> format  
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
<td align="left"><pre><code>public <a href="../../FrameDescription_Class.md">FrameDescription</a>CreateFrameDescription (  
         <a href="../../ColorImageFormat_Enumeration.md">ColorImageFormat</a> format  
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
<td align="left"><pre><code>var frameDescription = colorFrameSource.createFrameDescription(format);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EJ"></span>
#### Parameters  

*format*    
Type: [ColorImageFormat](../../ColorImageFormat_Enumeration.md)  
 The image format for which to create the FrameDescription object.  

<span id="ID4ES"></span>
#### Return value  

Type: [FrameDescription](../../FrameDescription_Class.md)  
 A new FrameDescription object for the ColorFrame of the requested format.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EJB"></span>

See also  
========  

<span id="ID4ELB"></span>
#### Reference  

[ColorFrameSource Class](../../ColorFrameSource_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CreateFrameDescription Method
RLTitle : ColorFrameSource.CreateFrameDescription Method
KeywordK : CreateFrameDescription method
KeywordK : ColorFrameSource.CreateFrameDescription method
KeywordF : WindowsPreview.Kinect.ColorFrameSource.CreateFrameDescription
KeywordF : ColorFrameSource.CreateFrameDescription
KeywordF : CreateFrameDescription
KeywordF : WindowsPreview.Kinect.ColorFrameSource.CreateFrameDescription(WindowsPreview.Kinect.ColorImageFormat)
KeywordA : M:WindowsPreview.Kinect.ColorFrameSource.CreateFrameDescription(WindowsPreview.Kinect.ColorImageFormat)
AssetID : M:WindowsPreview.Kinect.ColorFrameSource.CreateFrameDescription(WindowsPreview.Kinect.ColorImageFormat)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrameSource.CreateFrameDescription
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
