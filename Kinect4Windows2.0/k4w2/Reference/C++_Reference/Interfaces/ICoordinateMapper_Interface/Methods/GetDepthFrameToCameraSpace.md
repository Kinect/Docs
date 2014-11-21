ICoordinateMapper::GetDepthFrameToCameraSpaceTable Method  
=========================================================  

Generates a table of camera space points. <span id="syntaxSection"></span>

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
HRESULT GetDepthFrameToCameraSpaceTable(  
         UINT32 *tableEntryCount,  
         PointF **tableEntries  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*tableEntryCount*    
Type: UINT32  
[out] The number of camera space points.  

*tableEntries*    
Type: PointF  
[out] The table of camera space points.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The table of camera space points must be released with a call to [CoTaskMemFree](http://go.microsoft.com/fwlink/?LinkId=510209).  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetDepthFrameToCameraSpaceTable Method
RLTitle : ICoordinateMapper::GetDepthFrameToCameraSpaceTable Method
KeywordK : GetDepthFrameToCameraSpaceTable method
KeywordK : ICoordinateMapper::GetDepthFrameToCameraSpaceTable method
KeywordF : ICoordinateMapper::GetDepthFrameToCameraSpaceTable
KeywordF : GetDepthFrameToCameraSpaceTable
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.GetDepthFrameToCameraSpaceTable(UINT32@,PointF@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.GetDepthFrameToCameraSpaceTable(UINT32@,PointF@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.GetDepthFrameToCameraSpaceTable(UINT32@,PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::GetDepthFrameToCameraSpaceTable
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
