IKinectGestureRecognizer::get\_IsActive Method  
==============================================  

Gets a value that indicates whether an interaction is being processed. <span id="syntaxSection"></span>

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
HRESULT get_IsActive(  
         boolean *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: boolean  
[out] True if the interaction (including inertia) is still being processed; otherwise false. The default value is false.  

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
TOCTitle : get_IsActive Method
RLTitle : IKinectGestureRecognizer::get_IsActive Method
KeywordK : get_IsActive method
KeywordK : IKinectGestureRecognizer::get_IsActive method
KeywordF : IKinectGestureRecognizer::get_IsActive
KeywordF : get_IsActive
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_IsActive(boolean@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_IsActive(boolean@)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_IsActive(boolean@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::get_IsActive
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
