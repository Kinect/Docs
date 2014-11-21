IKinectPointerPointProperties::get\_BodyTrackingId Method  
=========================================================  

Gets a unique identifier that associates the pointer with a [IBody](../../IBody_Interface.md) object. <span id="syntaxSection"></span>

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
HRESULT get_BodyTrackingId(  
         UINT64 *bodyTrackingId  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*bodyTrackingId*    
Type: UINT64  
[out] A unique identifier that associates the pointer with a [IBody](../../IBody_Interface.md) object.  

<span id="ID4ET"></span>
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
TOCTitle : get_BodyTrackingId Method
RLTitle : IKinectPointerPointProperties::get_BodyTrackingId Method
KeywordK : get_BodyTrackingId method
KeywordK : IKinectPointerPointProperties::get_BodyTrackingId method
KeywordF : IKinectPointerPointProperties::get_BodyTrackingId
KeywordF : get_BodyTrackingId
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_BodyTrackingId(UINT64@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_BodyTrackingId(UINT64@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_BodyTrackingId(UINT64@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPointProperties::get_BodyTrackingId
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
