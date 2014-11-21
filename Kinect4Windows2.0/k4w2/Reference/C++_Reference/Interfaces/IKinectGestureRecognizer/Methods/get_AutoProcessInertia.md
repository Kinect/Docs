IKinectGestureRecognizer::get\_AutoProcessInertia Method  
========================================================  

Gets a value that indicates whether manipulations during inertia are generated automatically. If false, the app is expected to call ProcessInertia periodically. <span id="syntaxSection"></span>

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
HRESULT get_AutoProcessInertia(  
         boolean *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: boolean  
[out] True if manipulations are generated automatically; otherwise false. The default value is true.  

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
TOCTitle : get_AutoProcessInertia Method
RLTitle : IKinectGestureRecognizer::get_AutoProcessInertia Method
KeywordK : get_AutoProcessInertia method
KeywordK : IKinectGestureRecognizer::get_AutoProcessInertia method
KeywordF : IKinectGestureRecognizer::get_AutoProcessInertia
KeywordF : get_AutoProcessInertia
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_AutoProcessInertia(boolean@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_AutoProcessInertia(boolean@)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_AutoProcessInertia(boolean@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::get_AutoProcessInertia
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
