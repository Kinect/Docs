IFaceAlignment::GetAnimationUnits Method  
========================================  

Gets the animation units. <span id="syntaxSection"></span>

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
HRESULT GetAnimationUnits(  
         UINT capacity,  
         float *animationUnits  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
The capacity of the array specified with the animationUnits parameter.  

*animationUnits*    
Type: float  
[out] The array that will be populated with animation units.  

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
TOCTitle : GetAnimationUnits Method
RLTitle : IFaceAlignment::GetAnimationUnits Method
KeywordK : GetAnimationUnits method
KeywordK : IFaceAlignment::GetAnimationUnits method
KeywordF : IFaceAlignment::GetAnimationUnits
KeywordF : GetAnimationUnits
KeywordF : Microsoft.Kinect.face.IFaceAlignment.GetAnimationUnits(UINT,float@)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.GetAnimationUnits(UINT,float@)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.GetAnimationUnits(UINT,float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::GetAnimationUnits
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
