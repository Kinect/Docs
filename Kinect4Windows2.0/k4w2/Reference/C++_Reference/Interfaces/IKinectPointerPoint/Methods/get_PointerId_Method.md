IKinectPointerPoint::get\_PointerId Method  
==========================================  

Gets a unique identifier for the input pointer. <span id="syntaxSection"></span>

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
HRESULT get_PointerId(  
         UINT32 *pointerId  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pointerId*    
Type: UINT32  
[out] A unique value that identifies the input pointer.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_PointerId Method
RLTitle : IKinectPointerPoint::get_PointerId Method
KeywordK : get_PointerId method
KeywordK : IKinectPointerPoint::get_PointerId method
KeywordF : IKinectPointerPoint::get_PointerId
KeywordF : get_PointerId
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPoint.get_PointerId(UINT32@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_PointerId(UINT32@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_PointerId(UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPoint::get_PointerId
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
