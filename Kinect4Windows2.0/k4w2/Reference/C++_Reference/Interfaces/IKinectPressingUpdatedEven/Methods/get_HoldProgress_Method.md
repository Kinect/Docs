IKinectPressingUpdatedEventArgs::get\_HoldProgress Method  
=========================================================  

Gets a normalized value indicating the progress of a hold gesture. <span id="syntaxSection"></span>

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
HRESULT get_HoldProgress(  
         float *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: float  
[out] A normalized value indicating the progress of a hold gesture.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

This value is 0.0 when a hold gesture starts and increases to 1.0, which indicates the hold gesture is complete.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_HoldProgress Method
RLTitle : IKinectPressingUpdatedEventArgs::get_HoldProgress Method
KeywordK : get_HoldProgress method
KeywordK : IKinectPressingUpdatedEventArgs::get_HoldProgress method
KeywordF : IKinectPressingUpdatedEventArgs::get_HoldProgress
KeywordF : get_HoldProgress
KeywordF : Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs.get_HoldProgress(float@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs.get_HoldProgress(float@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs.get_HoldProgress(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs::get_HoldProgress
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
