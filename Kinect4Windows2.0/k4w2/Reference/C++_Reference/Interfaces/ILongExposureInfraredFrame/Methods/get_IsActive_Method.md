ILongExposureInfraredFrameSource::get\_IsActive Method  
======================================================  

Gets whether the long exposure infrared frame source is active. <span id="syntaxSection"></span>

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
         BOOLEAN *isActive  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isActive*    
Type: BOOLEAN  
[out] Returns **true** if the long exposure infrared frame source is active; **false** otherwise.  

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
TOCTitle : get_IsActive Method
RLTitle : ILongExposureInfraredFrameSource::get_IsActive Method
KeywordK : get_IsActive method
KeywordK : ILongExposureInfraredFrameSource::get_IsActive method
KeywordF : ILongExposureInfraredFrameSource::get_IsActive
KeywordF : get_IsActive
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.get_IsActive(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.get_IsActive(BOOLEAN@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource.get_IsActive(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameSource::get_IsActive
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
