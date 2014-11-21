IFaceFrameSource::OpenReader Method  
===================================  

Creates a frame reader for the face frame source. <span id="syntaxSection"></span>

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
HRESULT OpenReader(  
         IFaceFrameReader **reader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*reader*    
Type: IFaceFrameReader  
[out] A new frame reader for the face frame source.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenReader Method
RLTitle : IFaceFrameSource::OpenReader Method
KeywordK : OpenReader method
KeywordK : IFaceFrameSource::OpenReader method
KeywordF : IFaceFrameSource::OpenReader
KeywordF : OpenReader
KeywordF : Microsoft.Kinect.face.IFaceFrameSource.OpenReader(IFaceFrameReader@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameSource.OpenReader(IFaceFrameReader@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameSource.OpenReader(IFaceFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameSource::OpenReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
