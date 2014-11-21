ColorSpacePoint Structure  
=========================  

A 2D location in color space. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _ColorSpacePoint {  
    float X;  
    float Y;  
} ColorSpacePoint;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**X**    
The X component in color space.  

**Y**    
The Y component in color space.  

<span id="remarks"></span>

Remarks  
=======  

A color space point describes a 2D point on the color image. So a position in color space is a row/column location of a pixel on the image, where x=0, y=0 is the pixel at the top left of the color image, and x=1919, y=1079 (width-1, height-1) corresponds to the bottom right.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ColorSpacePoint Structure
RLTitle : ColorSpacePoint Structure
KeywordK : ColorSpacePoint structure
KeywordF : ColorSpacePoint
KeywordF : Microsoft.Kinect.kinect.ColorSpacePoint
KeywordA : T:Microsoft.Kinect.kinect.ColorSpacePoint
AssetID : T:Microsoft.Kinect.kinect.ColorSpacePoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ColorSpacePoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
