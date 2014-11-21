ILongExposureInfraredFrameReader::get\_IsPaused Method  
======================================================  

Gets whether the long exposure infrared frame reader is paused. <span id="syntaxSection"></span>

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
HRESULT get_IsPaused(  
         BOOLEAN *isPaused  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isPaused*    
Type: BOOLEAN  
[out] Returns **true** if the long exposure infrared frame reader is paused; **false** otherwise.  

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
TOCTitle : get_IsPaused Method
RLTitle : ILongExposureInfraredFrameReader::get_IsPaused Method
KeywordK : get_IsPaused method
KeywordK : ILongExposureInfraredFrameReader::get_IsPaused method
KeywordF : ILongExposureInfraredFrameReader::get_IsPaused
KeywordF : get_IsPaused
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader.get_IsPaused(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader.get_IsPaused(BOOLEAN@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader.get_IsPaused(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader::get_IsPaused
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
