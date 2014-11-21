DepthSpacePoint Structure  
=========================  

A 2D location in depth space. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _DepthSpacePoint {  
    float X;  
    float Y;  
} DepthSpacePoint;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**X**    
The X component in depth space.  

**Y**    
The Y component in depth space.  

<span id="remarks"></span>

Remarks  
=======  

Depth space is the term used to describe a 2D location on the depth image. Think of this as a row/column location of a pixel where x is the column and y is the row. So x=0, y=0 corresponds to the top left corner of the image and x=511, y=423 (width-1, height-1) is the bottom right corner of the image. In some cases, a z value is needed in order to map out of depth space. For these cases, simply sample the depth image at the row/column in question, and use that value (which is depth in millimeters) directly as z.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DepthSpacePoint Structure
RLTitle : DepthSpacePoint Structure
KeywordK : DepthSpacePoint structure
KeywordF : DepthSpacePoint
KeywordF : Microsoft.Kinect.kinect.DepthSpacePoint
KeywordA : T:Microsoft.Kinect.kinect.DepthSpacePoint
AssetID : T:Microsoft.Kinect.kinect.DepthSpacePoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.DepthSpacePoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
