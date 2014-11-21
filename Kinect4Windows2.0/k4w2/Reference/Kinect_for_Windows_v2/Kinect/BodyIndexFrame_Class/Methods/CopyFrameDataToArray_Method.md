BodyIndexFrame.CopyFrameDataToArray Method  
==========================================  

Copies the body index frame data into the array provided. <span id="syntaxSection"></span>

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
void CopyFrameDataToArray(  
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
<td align="left"><pre><code>public void CopyFrameDataToArray (  
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
<td align="left"><pre><code>bodyIndexFrame.copyFrameDataToArray();</code></pre></td>
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

<span id="remarks"></span>

Remarks  
=======  

Allocate the **frameData** array before calling this method. It should have the same number of elements as the depth frame has depth pixels (512px by 424px). Each array position that represents a depth pixel that belongs to a body will contain an index into the array of bodies in the frame. Array positions that correspond to depth pixels that do not belong to a body will contain the value 255.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EBB"></span>

See also  
========  

<span id="ID4EDB"></span>
#### Reference  

[BodyIndexFrame Class](../../BodyIndexFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyFrameDataToArray Method
RLTitle : BodyIndexFrame.CopyFrameDataToArray Method
KeywordK : CopyFrameDataToArray method
KeywordK : BodyIndexFrame.CopyFrameDataToArray method
KeywordF : WindowsPreview.Kinect.BodyIndexFrame.CopyFrameDataToArray
KeywordF : BodyIndexFrame.CopyFrameDataToArray
KeywordF : CopyFrameDataToArray
KeywordF : WindowsPreview.Kinect.BodyIndexFrame.CopyFrameDataToArray(System.Byte[]@)
KeywordA : M:WindowsPreview.Kinect.BodyIndexFrame.CopyFrameDataToArray(System.Byte[]@)
AssetID : M:WindowsPreview.Kinect.BodyIndexFrame.CopyFrameDataToArray(System.Byte[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyIndexFrame.CopyFrameDataToArray
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
