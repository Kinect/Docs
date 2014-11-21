IBody::GetAppearanceDetectionResults Method  
===========================================  

Gets the appearance. <span id="syntaxSection"></span>

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
HRESULT GetAppearanceDetectionResults(  
         _Pre_equal_to_(Appearance_Count)UINT capacity,  
         DetectionResult *detectionResults  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: \_Pre\_equal\_to\_(Appearance\_Count)UINT  
The number of appearances.  

*detectionResults*    
Type: DetectionResult  
[out] Gesture detection results.  

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
TOCTitle : GetAppearanceDetectionResults Method
RLTitle : IBody::GetAppearanceDetectionResults Method
KeywordK : GetAppearanceDetectionResults method
KeywordK : IBody::GetAppearanceDetectionResults method
KeywordF : IBody::GetAppearanceDetectionResults
KeywordF : GetAppearanceDetectionResults
KeywordF : Microsoft.Kinect.kinect.IBody.GetAppearanceDetectionResults(_Pre_equal_to_(Appearance_Count)UINT,DetectionResult@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.GetAppearanceDetectionResults(_Pre_equal_to_(Appearance_Count)UINT,DetectionResult@)
AssetID : M:Microsoft.Kinect.kinect.IBody.GetAppearanceDetectionResults(_Pre_equal_to_(Appearance_Count)UINT,DetectionResult@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::GetAppearanceDetectionResults
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
