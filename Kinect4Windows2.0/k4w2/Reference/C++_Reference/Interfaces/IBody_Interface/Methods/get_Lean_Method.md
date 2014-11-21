IBody::get\_Lean Method  
=======================  

Gets the amount a body is leaning, which is a number between -1 (leaning left or back) and 1 (leaning right or front). <span id="syntaxSection"></span>

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
HRESULT get_Lean(  
         PointF *amount  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*amount*    
Type: PointF  
[out] The body lean.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

Leaning left and right corresponds to X movement and leaning forward and back corresponds to Y movement.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_Lean Method
RLTitle : IBody::get_Lean Method
KeywordK : get_Lean method
KeywordK : IBody::get_Lean method
KeywordF : IBody::get_Lean
KeywordF : get_Lean
KeywordF : Microsoft.Kinect.kinect.IBody.get_Lean(PointF@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_Lean(PointF@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_Lean(PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_Lean
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
