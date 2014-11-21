IKinectPointerPoint::get\_PointerDevice Method  
==============================================  

Gets the pointer device associated with the pointer point. <span id="syntaxSection"></span>

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
HRESULT get_PointerDevice(  
         IKinectPointerDevice **ppPointerDevice  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*ppPointerDevice*    
Type: IKinectPointerDevice  
[out] The pointer device associated with the pointer point.  

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
TOCTitle : get_PointerDevice Method
RLTitle : IKinectPointerPoint::get_PointerDevice Method
KeywordK : get_PointerDevice method
KeywordK : IKinectPointerPoint::get_PointerDevice method
KeywordF : IKinectPointerPoint::get_PointerDevice
KeywordF : get_PointerDevice
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPoint.get_PointerDevice(IKinectPointerDevice@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_PointerDevice(IKinectPointerDevice@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_PointerDevice(IKinectPointerDevice@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPoint::get_PointerDevice
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
