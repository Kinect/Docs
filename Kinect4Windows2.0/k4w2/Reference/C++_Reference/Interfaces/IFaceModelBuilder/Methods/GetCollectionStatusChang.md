IFaceModelBuilder::GetCollectionStatusChangedEventData Method  
=============================================================  

Gets data for the CollectionStatusChanged event. <span id="syntaxSection"></span>

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
HRESULT GetCollectionStatusChangedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ICollectionStatusChangedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] The handle to the event.  

*eventData*    
Type: ICollectionStatusChangedEventArgs  
[out] The event data.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetCollectionStatusChangedEventData Method
RLTitle : IFaceModelBuilder::GetCollectionStatusChangedEventData Method
KeywordK : GetCollectionStatusChangedEventData method
KeywordK : IFaceModelBuilder::GetCollectionStatusChangedEventData method
KeywordF : IFaceModelBuilder::GetCollectionStatusChangedEventData
KeywordF : GetCollectionStatusChangedEventData
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.GetCollectionStatusChangedEventData(WAITABLE_HANDLE,ICollectionStatusChangedEventArgs@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCollectionStatusChangedEventData(WAITABLE_HANDLE,ICollectionStatusChangedEventArgs@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCollectionStatusChangedEventData(WAITABLE_HANDLE,ICollectionStatusChangedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::GetCollectionStatusChangedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
