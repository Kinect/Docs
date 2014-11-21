IKinectPointerEventArgs::get\_CurrentPoint Method  
=================================================  

Gets the pointer data of the last pointer event. <span id="syntaxSection"></span>

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
HRESULT get_CurrentPoint(  
         IKinectPointerPoint **pointer  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pointer*    
Type: IKinectPointerPoint  
[out] Information about the state and screen position of the pointer.  

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
TOCTitle : get_CurrentPoint Method
RLTitle : IKinectPointerEventArgs::get_CurrentPoint Method
KeywordK : get_CurrentPoint method
KeywordK : IKinectPointerEventArgs::get_CurrentPoint method
KeywordF : IKinectPointerEventArgs::get_CurrentPoint
KeywordF : get_CurrentPoint
KeywordF : Microsoft.Kinect.kinect.IKinectPointerEventArgs.get_CurrentPoint(IKinectPointerPoint@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectPointerEventArgs.get_CurrentPoint(IKinectPointerPoint@)
AssetID : M:Microsoft.Kinect.kinect.IKinectPointerEventArgs.get_CurrentPoint(IKinectPointerPoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerEventArgs::get_CurrentPoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
