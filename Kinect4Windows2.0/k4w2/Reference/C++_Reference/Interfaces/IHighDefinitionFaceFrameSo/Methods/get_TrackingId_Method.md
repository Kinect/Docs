IHighDefinitionFaceFrameSource::get\_TrackingId Method  
======================================================  

Gets the tracking ID for the high definition frame source. <span id="syntaxSection"></span>

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
HRESULT get_TrackingId(  
         UINT64 *trackingId  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*trackingId*    
Type: UINT64  
[out] The tracking ID for the face frame source.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_TrackingId Method
RLTitle : IHighDefinitionFaceFrameSource::get_TrackingId Method
KeywordK : get_TrackingId method
KeywordK : IHighDefinitionFaceFrameSource::get_TrackingId method
KeywordF : IHighDefinitionFaceFrameSource::get_TrackingId
KeywordF : get_TrackingId
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.get_TrackingId(UINT64@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.get_TrackingId(UINT64@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.get_TrackingId(UINT64@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::get_TrackingId
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
