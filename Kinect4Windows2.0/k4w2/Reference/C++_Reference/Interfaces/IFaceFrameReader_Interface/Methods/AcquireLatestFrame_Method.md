IFaceFrameReader::AcquireLatestFrame Method  
===========================================  

Gets the most recent face frame. <span id="syntaxSection"></span>

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
         IFaceFrame **faceFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceFrame*    
Type: IFaceFrame  
[out] The most recent face frame.  

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
RLTitle : IFaceFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : IFaceFrameReader::AcquireLatestFrame method
KeywordF : IFaceFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.face.IFaceFrameReader.AcquireLatestFrame(IFaceFrame@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameReader.AcquireLatestFrame(IFaceFrame@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameReader.AcquireLatestFrame(IFaceFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
