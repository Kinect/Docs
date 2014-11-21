IKinectPointerPoint::get\_Timestamp Method  
==========================================  

Gets the timestamp of the pointer point. <span id="syntaxSection"></span>

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
HRESULT get_Timestamp(  
         UINT64 *timestamp  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*timestamp*    
Type: UINT64  
[out] The timestamp of the pointer point.  

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
TOCTitle : get_Timestamp Method
RLTitle : IKinectPointerPoint::get_Timestamp Method
KeywordK : get_Timestamp method
KeywordK : IKinectPointerPoint::get_Timestamp method
KeywordF : IKinectPointerPoint::get_Timestamp
KeywordF : get_Timestamp
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPoint.get_Timestamp(UINT64@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_Timestamp(UINT64@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_Timestamp(UINT64@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPoint::get_Timestamp
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
