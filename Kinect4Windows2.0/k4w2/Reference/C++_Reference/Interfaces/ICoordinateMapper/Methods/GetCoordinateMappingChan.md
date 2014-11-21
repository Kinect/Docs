ICoordinateMapper::GetCoordinateMappingChangedEventData Method  
==============================================================  

Gets event data when the mapping between types of points changes. <span id="syntaxSection"></span>

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
HRESULT GetCoordinateMappingChangedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ICoordinateMappingChangedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to the event handler.  

*eventData*    
Type: ICoordinateMappingChangedEventArgs  
[out] The event data.  

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
TOCTitle : GetCoordinateMappingChangedEventData Method
RLTitle : ICoordinateMapper::GetCoordinateMappingChangedEventData Method
KeywordK : GetCoordinateMappingChangedEventData method
KeywordK : ICoordinateMapper::GetCoordinateMappingChangedEventData method
KeywordF : ICoordinateMapper::GetCoordinateMappingChangedEventData
KeywordF : GetCoordinateMappingChangedEventData
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper.GetCoordinateMappingChangedEventData(WAITABLE_HANDLE,ICoordinateMappingChangedEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.ICoordinateMapper.GetCoordinateMappingChangedEventData(WAITABLE_HANDLE,ICoordinateMappingChangedEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.ICoordinateMapper.GetCoordinateMappingChangedEventData(WAITABLE_HANDLE,ICoordinateMappingChangedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper::GetCoordinateMappingChangedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
