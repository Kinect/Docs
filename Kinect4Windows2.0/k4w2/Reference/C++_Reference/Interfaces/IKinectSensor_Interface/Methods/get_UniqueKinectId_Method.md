IKinectSensor::get\_UniqueKinectId Method  
=========================================  

Gets the unique ID of the Kinect sensor. <span id="syntaxSection"></span>

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
HRESULT get_UniqueKinectId(  
         UINT bufferSize,  
         WCHAR *uniqueKinectId  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bufferSize*    
Type: UINT  
The size of the string buffer that will contain the ID.  

*uniqueKinectId*    
Type: WCHAR  
[out] Unique ID of the Kinect sensor.  

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
TOCTitle : get_UniqueKinectId Method
RLTitle : IKinectSensor::get_UniqueKinectId Method
KeywordK : get_UniqueKinectId method
KeywordK : IKinectSensor::get_UniqueKinectId method
KeywordF : IKinectSensor::get_UniqueKinectId
KeywordF : get_UniqueKinectId
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.get_UniqueKinectId(UINT,WCHAR@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.get_UniqueKinectId(UINT,WCHAR@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.get_UniqueKinectId(UINT,WCHAR@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::get_UniqueKinectId
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
