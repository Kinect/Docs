IKinectPointerPointProperties::get\_HandReachExtent Method  
==========================================================  

Gets a value indicating the distance along the Z axis of the hand from the shoulder. <span id="syntaxSection"></span>

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
HRESULT get_HandReachExtent(  
         float *handReachExtent  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*handReachExtent*    
Type: float  
[out] A value indicating the distance along the Z axis of the hand from the shoulder.  

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
TOCTitle : get_HandReachExtent Method
RLTitle : IKinectPointerPointProperties::get_HandReachExtent Method
KeywordK : get_HandReachExtent method
KeywordK : IKinectPointerPointProperties::get_HandReachExtent method
KeywordF : IKinectPointerPointProperties::get_HandReachExtent
KeywordF : get_HandReachExtent
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_HandReachExtent(float@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_HandReachExtent(float@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_HandReachExtent(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPointProperties::get_HandReachExtent
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
