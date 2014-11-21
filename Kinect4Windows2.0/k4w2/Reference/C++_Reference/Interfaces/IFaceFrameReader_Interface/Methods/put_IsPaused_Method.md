IFaceFrameReader::put\_IsPaused Method  
======================================  

Sets a boolean value that pauses or resumes the reader. <span id="syntaxSection"></span>

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
HRESULT put_IsPaused(  
         BOOLEAN isPaused  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isPaused*    
Type: BOOLEAN  
 Set **true** to pause the reader; **false** to resume.  

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
TOCTitle : put_IsPaused Method
RLTitle : IFaceFrameReader::put_IsPaused Method
KeywordK : put_IsPaused method
KeywordK : IFaceFrameReader::put_IsPaused method
KeywordF : IFaceFrameReader::put_IsPaused
KeywordF : put_IsPaused
KeywordF : Microsoft.Kinect.face.IFaceFrameReader.put_IsPaused(BOOLEAN)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameReader.put_IsPaused(BOOLEAN)
AssetID : M:Microsoft.Kinect.face.IFaceFrameReader.put_IsPaused(BOOLEAN)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameReader::put_IsPaused
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
