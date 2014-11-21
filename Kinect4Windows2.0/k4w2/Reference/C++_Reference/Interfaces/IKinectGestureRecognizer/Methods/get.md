IKinectGestureRecognizer::get\_InertiaTranslationDisplacement Method  
====================================================================  

Gets or sets a value that indicates the relative change in the screen location of an object from the start of inertia to the end of inertia (when the translation manipulation is complete). <span id="syntaxSection"></span>

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
HRESULT get_InertiaTranslationDisplacement(  
         float *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: float  
[out] The relative change in screen location, in DIPs.  

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
TOCTitle : get_InertiaTranslationDisplacement Method
RLTitle : IKinectGestureRecognizer::get_InertiaTranslationDisplacement Method
KeywordK : get_InertiaTranslationDisplacement method
KeywordK : IKinectGestureRecognizer::get_InertiaTranslationDisplacement method
KeywordF : IKinectGestureRecognizer::get_InertiaTranslationDisplacement
KeywordF : get_InertiaTranslationDisplacement
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_InertiaTranslationDisplacement(float@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_InertiaTranslationDisplacement(float@)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.get_InertiaTranslationDisplacement(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::get_InertiaTranslationDisplacement
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
