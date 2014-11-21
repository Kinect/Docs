IHighDefinitionFaceFrameReader::AcquireLatestFrame Method  
=========================================================  

Gets the most recent high definition face frame. <span id="syntaxSection"></span>

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
HRESULT AcquireLatestFrame(  
         IHighDefinitionFaceFrame **faceFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceFrame*    
Type: IHighDefinitionFaceFrame  
[out] The most recent high definition face frame.  

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
TOCTitle : AcquireLatestFrame Method
RLTitle : IHighDefinitionFaceFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : IHighDefinitionFaceFrameReader::AcquireLatestFrame method
KeywordF : IHighDefinitionFaceFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.AcquireLatestFrame(IHighDefinitionFaceFrame@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.AcquireLatestFrame(IHighDefinitionFaceFrame@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.AcquireLatestFrame(IHighDefinitionFaceFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
