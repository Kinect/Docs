IKinectSensor::get\_IsAvailable Method  
======================================  

Gets a boolean value that indicates whether the Kinect sensor is available. <span id="syntaxSection"></span>

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
HRESULT get_IsAvailable(  
         BOOLEAN *isAvailable  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isAvailable*    
Type: BOOLEAN  
[out] Returns **true** if the kinect sensor is available; **false** otherwise.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_IsAvailable Method
RLTitle : IKinectSensor::get_IsAvailable Method
KeywordK : get_IsAvailable method
KeywordK : IKinectSensor::get_IsAvailable method
KeywordF : IKinectSensor::get_IsAvailable
KeywordF : get_IsAvailable
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.get_IsAvailable(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.get_IsAvailable(BOOLEAN@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.get_IsAvailable(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::get_IsAvailable
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
