IKinectPointerPointProperties::get\_PressExtent Method  
======================================================  

Gets a normalized Z value for a pressing gesture. <span id="syntaxSection"></span>

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
HRESULT get_PressExtent(  
         float *pressExtent  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pressExtent*    
Type: float  
[out] A normalized Z value for a pressing gesture.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The value of this property is 0.0 when a pressing gesture starts. As the user presses forward, the value increases until it reaches 1.0, which indicates the tappable gesture recognizer has been pressed. The value decreases as the user moves the pointer backwards, although it will not go negative. The value is reset to 0.0 when a pressing gesture on another tappable gesture recognizer begins.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_PressExtent Method
RLTitle : IKinectPointerPointProperties::get_PressExtent Method
KeywordK : get_PressExtent method
KeywordK : IKinectPointerPointProperties::get_PressExtent method
KeywordF : IKinectPointerPointProperties::get_PressExtent
KeywordF : get_PressExtent
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_PressExtent(float@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_PressExtent(float@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerPointProperties.get_PressExtent(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPointProperties::get_PressExtent
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
