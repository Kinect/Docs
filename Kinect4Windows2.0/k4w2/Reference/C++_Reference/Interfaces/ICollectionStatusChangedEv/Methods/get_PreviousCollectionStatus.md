ICollectionStatusChangedEventArgs::get\_PreviousCollectionStatus Method  
=======================================================================  

Gets the capture status from before the [IFaceModelBuilder Interface](../../IFaceModelBuilder_Interface.md) CollectionStatusChanged event. <span id="syntaxSection"></span>

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
HRESULT get_PreviousCollectionStatus(  
         FaceModelBuilderCollectionStatus *pCollectionStatus  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*pCollectionStatus*    
Type: FaceModelBuilderCollectionStatus  
[out] The previous capture status.  

<span id="ID4ET"></span>
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
TOCTitle : get_PreviousCollectionStatus Method
RLTitle : ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus Method
KeywordK : get_PreviousCollectionStatus method
KeywordK : ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus method
KeywordF : ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus
KeywordF : get_PreviousCollectionStatus
KeywordF : Microsoft.Kinect.face.ICollectionStatusChangedEventArgs.get_PreviousCollectionStatus(FaceModelBuilderCollectionStatus@)
KeywordA : M:Microsoft.Kinect.face.ICollectionStatusChangedEventArgs.get_PreviousCollectionStatus(FaceModelBuilderCollectionStatus@)
AssetID : M:Microsoft.Kinect.face.ICollectionStatusChangedEventArgs.get_PreviousCollectionStatus(FaceModelBuilderCollectionStatus@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
