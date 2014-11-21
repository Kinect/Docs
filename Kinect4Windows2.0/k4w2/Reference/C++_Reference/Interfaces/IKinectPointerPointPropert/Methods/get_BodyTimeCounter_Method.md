IKinectPointerPointProperties::get\_BodyTimeCounter Method  
==========================================================  

Gets a time stamp to associate the pointer with a [IBody](../../IBody_Interface.md) object. <span id="syntaxSection"></span>

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
HRESULT get_BodyTimeCounter(  
         TIMESPAN *bodyTimeCounter  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*bodyTimeCounter*    
Type: TIMESPAN  
[out] A time stamp to associate the pointer with a [IBody](../../IBody_Interface.md) object.  

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
TOCTitle : get_BodyTimeCounter Method
RLTitle : IKinectPointerPointProperties::get_BodyTimeCounter Method
KeywordK : get_BodyTimeCounter method
KeywordK : IKinectPointerPointProperties::get_BodyTimeCounter method
KeywordF : IKinectPointerPointProperties::get_BodyTimeCounter
KeywordF : get_BodyTimeCounter
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_BodyTimeCounter(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_BodyTimeCounter(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_BodyTimeCounter(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPointProperties::get_BodyTimeCounter
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
