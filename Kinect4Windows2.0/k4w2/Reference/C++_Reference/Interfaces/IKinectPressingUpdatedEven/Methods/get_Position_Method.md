IKinectPressingUpdatedEventArgs::get\_Position Method  
=====================================================  

Gets the location of the pointer associated with the manipulation for the last PressingUpdated event. <span id="syntaxSection"></span>

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
HRESULT get_Position(  
         PointF *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: PointF  
[out] The screen coordinates, in device-independent pixels (DIPs).  

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
TOCTitle : get_Position Method
RLTitle : IKinectPressingUpdatedEventArgs::get_Position Method
KeywordK : get_Position method
KeywordK : IKinectPressingUpdatedEventArgs::get_Position method
KeywordF : IKinectPressingUpdatedEventArgs::get_Position
KeywordF : get_Position
KeywordF : Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs.get_Position(PointF@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs.get_Position(PointF@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs.get_Position(PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPressingUpdatedEventArgs::get_Position
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
