ColorFrame.CopyConvertedFrameDataToArray Method  
===============================================  

Converts the raw format into the requested format and copies the data into the array provided. <span id="syntaxSection"></span>

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
void CopyConvertedFrameDataToArray(  
         out Array&lt;unsigned char&gt;^ frameData,  
         <a href="../../ColorImageFormat_Enumeration.md">ColorImageFormat</a> colorFormat  
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
<td align="left"><pre><code>public void CopyConvertedFrameDataToArray (  
         out Array&lt;byte&gt;[] frameData,  
         <a href="../../ColorImageFormat_Enumeration.md">ColorImageFormat</a> colorFormat  
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
<td align="left"><pre><code>colorFrame.copyConvertedFrameDataToArray(colorFormat);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frameData*    
[C++] Type: unsigned char  
  [C\#] Type: [byte](http://msdn.microsoft.com/en-us/library/system.byte.aspx)  
  [JavaScript] Type: Number  
   

The array to fill.  

*colorFormat*    
Type: [ColorImageFormat](../../ColorImageFormat_Enumeration.md)  
The desired color image format.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ECB"></span>

See also  
========  

<span id="ID4EEB"></span>
#### Reference  

[ColorFrame Class](../../ColorFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyConvertedFrameDataToArray Method
RLTitle : ColorFrame.CopyConvertedFrameDataToArray Method
KeywordK : CopyConvertedFrameDataToArray method
KeywordK : ColorFrame.CopyConvertedFrameDataToArray method
KeywordF : WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToArray
KeywordF : ColorFrame.CopyConvertedFrameDataToArray
KeywordF : CopyConvertedFrameDataToArray
KeywordF : WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToArray(System.Byte[]@,WindowsPreview.Kinect.ColorImageFormat)
KeywordA : M:WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToArray(System.Byte[]@,WindowsPreview.Kinect.ColorImageFormat)
AssetID : M:WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToArray(System.Byte[]@,WindowsPreview.Kinect.ColorImageFormat)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrame.CopyConvertedFrameDataToArray
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
