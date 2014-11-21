IFaceFrame::get\_FaceFrameResult Method  
=======================================  

Gets the face frame result. <span id="syntaxSection"></span>

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
HRESULT get_FaceFrameResult(  
         IFaceFrameResult **faceFrameResult  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceFrameResult*    
Type: IFaceFrameResult  
[out] The face frame result.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The return result can be null (even if S\_OK) and should be checked against nullptr.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_FaceFrameResult Method
RLTitle : IFaceFrame::get_FaceFrameResult Method
KeywordK : get_FaceFrameResult method
KeywordK : IFaceFrame::get_FaceFrameResult method
KeywordF : IFaceFrame::get_FaceFrameResult
KeywordF : get_FaceFrameResult
KeywordF : Microsoft.Kinect.face.IFaceFrame.get_FaceFrameResult(IFaceFrameResult@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrame.get_FaceFrameResult(IFaceFrameResult@)
AssetID : M:Microsoft.Kinect.face.IFaceFrame.get_FaceFrameResult(IFaceFrameResult@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrame::get_FaceFrameResult
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
