IKinectPointerPointProperties::get\_HandType Method  
===================================================  

Gets a value indicating whether the hand that is associated with the pointer is a identified as a user's right hand, left hand, or neither. <span id="syntaxSection"></span>

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
HRESULT get_HandType(  
         HandType *handType  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*handType*    
Type: HandType  
[out] A value indicating the hand type associated with the pointer.  

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
TOCTitle : get_HandType Method
RLTitle : IKinectPointerPointProperties::get_HandType Method
KeywordK : get_HandType method
KeywordK : IKinectPointerPointProperties::get_HandType method
KeywordF : IKinectPointerPointProperties::get_HandType
KeywordF : get_HandType
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_HandType(HandType@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_HandType(HandType@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_HandType(HandType@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPointProperties::get_HandType
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
