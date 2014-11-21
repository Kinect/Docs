IBody::GetActivityDetectionResults Method  
=========================================  

Gets the activity detection results from IBody. <span id="syntaxSection"></span>

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
HRESULT GetActivityDetectionResults(  
         _Pre_equal_to_(Activity_Count)UINT capacity,  
         DetectionResult *detectionResults  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: \_Pre\_equal\_to\_(Activity\_Count)UINT  
The size of the results.  

*detectionResults*    
Type: DetectionResult  
[out] The activity detection results.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

In the current release, the returned detection result is always DetectionResult\_Unknown.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetActivityDetectionResults Method
RLTitle : IBody::GetActivityDetectionResults Method
KeywordK : GetActivityDetectionResults method
KeywordK : IBody::GetActivityDetectionResults method
KeywordF : IBody::GetActivityDetectionResults
KeywordF : GetActivityDetectionResults
KeywordF : Microsoft.Kinect.kinect.IBody.GetActivityDetectionResults(_Pre_equal_to_(Activity_Count)UINT,DetectionResult@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.GetActivityDetectionResults(_Pre_equal_to_(Activity_Count)UINT,DetectionResult@)
AssetID : M:Microsoft.Kinect.kinect.IBody.GetActivityDetectionResults(_Pre_equal_to_(Activity_Count)UINT,DetectionResult@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::GetActivityDetectionResults
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
