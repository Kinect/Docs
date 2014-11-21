IKinectGestureRecognizer::get\_IsInertial Method  
================================================  

Gets a value that indicates whether a manipulation is still being processed during inertia (no input points are active). <span id="syntaxSection"></span>

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
HRESULT get_IsInertial(  
         boolean *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: boolean  
[out] True if the manipulation is still being processed during inertia; otherwise false. The default value is false.  

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
TOCTitle : get_IsInertial Method
RLTitle : IKinectGestureRecognizer::get_IsInertial Method
KeywordK : get_IsInertial method
KeywordK : IKinectGestureRecognizer::get_IsInertial method
KeywordF : IKinectGestureRecognizer::get_IsInertial
KeywordF : get_IsInertial
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_IsInertial(boolean@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_IsInertial(boolean@)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_IsInertial(boolean@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::get_IsInertial
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
