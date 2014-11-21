ColorFrame.CopyRawFrameDataToArray Method  
=========================================  

Copies the raw frame data into the array provided. <span id="syntaxSection"></span>

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
void CopyRawFrameDataToArray(  
         out Array&lt;unsigned char&gt;^ frameData  
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
<td align="left"><pre><code>public void CopyRawFrameDataToArray (  
         out Array&lt;byte&gt;[] frameData  
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
<td align="left"><pre><code>colorFrame.copyRawFrameDataToArray();</code></pre></td>
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

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[ColorFrame Class](../../ColorFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyRawFrameDataToArray Method
RLTitle : ColorFrame.CopyRawFrameDataToArray Method
KeywordK : CopyRawFrameDataToArray method
KeywordK : ColorFrame.CopyRawFrameDataToArray method
KeywordF : WindowsPreview.Kinect.ColorFrame.CopyRawFrameDataToArray
KeywordF : ColorFrame.CopyRawFrameDataToArray
KeywordF : CopyRawFrameDataToArray
KeywordF : WindowsPreview.Kinect.ColorFrame.CopyRawFrameDataToArray(System.Byte[]@)
KeywordA : M:WindowsPreview.Kinect.ColorFrame.CopyRawFrameDataToArray(System.Byte[]@)
AssetID : M:WindowsPreview.Kinect.ColorFrame.CopyRawFrameDataToArray(System.Byte[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrame.CopyRawFrameDataToArray
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
