IKinectManipulationUpdatedEventArgs::get\_Delta Method  
======================================================  

Gets values that indicate the changes in the transformation deltas (translation, rotation, scale) of a manipulation since the last manipulation event. <span id="syntaxSection"></span>

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
HRESULT get_Delta(  
         KinectManipulationDelta *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: KinectManipulationDelta  
[out] The changes in transformation values since the last event.  

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
TOCTitle : get_Delta Method
RLTitle : IKinectManipulationUpdatedEventArgs::get_Delta Method
KeywordK : get_Delta method
KeywordK : IKinectManipulationUpdatedEventArgs::get_Delta method
KeywordF : IKinectManipulationUpdatedEventArgs::get_Delta
KeywordF : get_Delta
KeywordF : Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs.get_Delta(KinectManipulationDelta@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs.get_Delta(KinectManipulationDelta@)
AssetID : M:Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs.get_Delta(KinectManipulationDelta@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs::get_Delta
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
