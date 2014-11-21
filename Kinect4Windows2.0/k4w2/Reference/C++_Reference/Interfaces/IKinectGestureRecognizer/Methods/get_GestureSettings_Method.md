IKinectGestureRecognizer::get\_GestureSettings Method  
=====================================================  

Sets a value that indicates the gesture and manipulation settings supported by an application. <span id="syntaxSection"></span>

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
HRESULT get_GestureSettings(  
         KinectGestureSettings *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: KinectGestureSettings  
[out] The gesture settings supported by an application. The value of this property is a bitwise OR of members of GestureSettings enumeration.  

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
TOCTitle : get_GestureSettings Method
RLTitle : IKinectGestureRecognizer::get_GestureSettings Method
KeywordK : get_GestureSettings method
KeywordK : IKinectGestureRecognizer::get_GestureSettings method
KeywordF : IKinectGestureRecognizer::get_GestureSettings
KeywordF : get_GestureSettings
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_GestureSettings(KinectGestureSettings@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_GestureSettings(KinectGestureSettings@)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_GestureSettings(KinectGestureSettings@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::get_GestureSettings
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
