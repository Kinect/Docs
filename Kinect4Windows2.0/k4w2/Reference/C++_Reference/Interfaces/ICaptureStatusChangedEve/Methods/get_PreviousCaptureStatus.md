ICaptureStatusChangedEventArgs::get\_PreviousCaptureStatus Method  
=================================================================  

Gets the capture status from before the [IFaceModelBuilder Interface](../../IFaceModelBuilder.md) CaptureStatusChanged event. <span id="syntaxSection"></span>

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
HRESULT get_PreviousCaptureStatus(  
         FaceModelBuilderCaptureStatus *pCaptureStatus  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*pCaptureStatus*    
Type: FaceModelBuilderCaptureStatus  
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
TOCTitle : get_PreviousCaptureStatus Method
RLTitle : ICaptureStatusChangedEventArgs::get_PreviousCaptureStatus Method
KeywordK : get_PreviousCaptureStatus method
KeywordK : ICaptureStatusChangedEventArgs::get_PreviousCaptureStatus method
KeywordF : ICaptureStatusChangedEventArgs::get_PreviousCaptureStatus
KeywordF : get_PreviousCaptureStatus
KeywordF : Microsoft.Kinect.face.ICaptureStatusChangedEventArgs.get_PreviousCaptureStatus(FaceModelBuilderCaptureStatus@)
KeywordA : M:Microsoft.Kinect.face.ICaptureStatusChangedEventArgs.get_PreviousCaptureStatus(FaceModelBuilderCaptureStatus@)
AssetID : M:Microsoft.Kinect.face.ICaptureStatusChangedEventArgs.get_PreviousCaptureStatus(FaceModelBuilderCaptureStatus@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.ICaptureStatusChangedEventArgs::get_PreviousCaptureStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
