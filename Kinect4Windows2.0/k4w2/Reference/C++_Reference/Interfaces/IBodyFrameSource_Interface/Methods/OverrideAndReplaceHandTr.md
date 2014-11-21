IBodyFrameSource::OverrideAndReplaceHandTracking Method  
=======================================================  

Override hand tracking the old tracking id and replace it with the new tracking id. <span id="syntaxSection"></span>

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
HRESULT OverrideAndReplaceHandTracking(  
         UINT64 oldTrackingId,  
         UINT64 newTrackingId  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*oldTrackingId*    
Type: UINT64  
The old tracking id.  

*newTrackingId*    
Type: UINT64  
The new tracking id.  

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
TOCTitle : OverrideAndReplaceHandTracking Method
RLTitle : IBodyFrameSource::OverrideAndReplaceHandTracking Method
KeywordK : OverrideAndReplaceHandTracking method
KeywordK : IBodyFrameSource::OverrideAndReplaceHandTracking method
KeywordF : IBodyFrameSource::OverrideAndReplaceHandTracking
KeywordF : OverrideAndReplaceHandTracking
KeywordF : Microsoft.Kinect.kinect.IBodyFrameSource.OverrideAndReplaceHandTracking(UINT64,UINT64)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrameSource.OverrideAndReplaceHandTracking(UINT64,UINT64)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrameSource.OverrideAndReplaceHandTracking(UINT64,UINT64)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameSource::OverrideAndReplaceHandTracking
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
