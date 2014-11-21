IEnumKinectSensor::GetNext Method  
=================================  

Gets the next attached Kinect sensor in the collection. <span id="syntaxSection"></span>

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
HRESULT GetNext(  
         IKinectSensor **sensor  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sensor*    
Type: IKinectSensor  
[out] The next Kinect sensor.  

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
TOCTitle : GetNext Method
RLTitle : IEnumKinectSensor::GetNext Method
KeywordK : GetNext method
KeywordK : IEnumKinectSensor::GetNext method
KeywordF : IEnumKinectSensor::GetNext
KeywordF : GetNext
KeywordF : Microsoft.Kinect.kinect.IEnumKinectSensor.GetNext(IKinectSensor@)
KeywordA : M:Microsoft.Kinect.kinect.IEnumKinectSensor.GetNext(IKinectSensor@)
AssetID : M:Microsoft.Kinect.kinect.IEnumKinectSensor.GetNext(IKinectSensor@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IEnumKinectSensor::GetNext
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
