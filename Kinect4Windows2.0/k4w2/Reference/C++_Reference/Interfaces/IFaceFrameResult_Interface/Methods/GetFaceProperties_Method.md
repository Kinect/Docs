IFaceFrameResult::GetFaceProperties Method  
==========================================  

Gets the face properties. <span id="syntaxSection"></span>

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
HRESULT GetFaceProperties(  
         const UINT capacity,  
         DetectionResult *detectionResults  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[in] The size of the detectionResults array.  

*detectionResults*    
Type: DetectionResult  
[out] The array in which the detection results will be stored.  

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
TOCTitle : GetFaceProperties Method
RLTitle : IFaceFrameResult::GetFaceProperties Method
KeywordK : GetFaceProperties method
KeywordK : IFaceFrameResult::GetFaceProperties method
KeywordF : IFaceFrameResult::GetFaceProperties
KeywordF : GetFaceProperties
KeywordF : Microsoft.Kinect.face.IFaceFrameResult.GetFaceProperties(UINT,DetectionResult@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameResult.GetFaceProperties(UINT,DetectionResult@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameResult.GetFaceProperties(UINT,DetectionResult@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult::GetFaceProperties
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
