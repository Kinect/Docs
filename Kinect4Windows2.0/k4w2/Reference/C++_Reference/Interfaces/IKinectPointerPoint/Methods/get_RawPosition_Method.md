IKinectPointerPoint::get\_RawPosition Method  
============================================  

Gets the client coordinates of the pointer point. <span id="syntaxSection"></span>

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
HRESULT get_RawPosition(  
         PointF *rawPosition  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*rawPosition*    
Type: PointF  
[out] The client coordinates, in device-independent pixels (DIPs).  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

RawPosition contains the client coordinates of the input pointer as reported by the input device. Under some circumstances, such as input prediction, this data can be modified by the system to compensate for hardware latency or message latency due to inherent delays in sensing and processing the pointer location on the digitizer.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_RawPosition Method
RLTitle : IKinectPointerPoint::get_RawPosition Method
KeywordK : get_RawPosition method
KeywordK : IKinectPointerPoint::get_RawPosition method
KeywordF : IKinectPointerPoint::get_RawPosition
KeywordF : get_RawPosition
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPoint.get_RawPosition(PointF@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_RawPosition(PointF@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPoint.get_RawPosition(PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPoint::get_RawPosition
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
