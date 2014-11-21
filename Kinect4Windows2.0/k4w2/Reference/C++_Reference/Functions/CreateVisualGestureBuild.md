CreateVisualGestureBuilderFrameSource  
=====================================  

Initializes a new [IVisualGestureBuilderFrameSource](../Interfaces/IVisualGestureBuilderFra.md). <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateVisualGestureBuilderFrameSource(  
         IKinectSensor *sensor,  
         UINT64 initialTrackingId,  
         IVisualGestureBuilderFrameSource **source  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EL"></span>
#### Parameters  

*sensor*    
Type: IKinectSensor  
[in] The Kinect sensor associated with the frame source.  

*initialTrackingId*    
Type: UINT64  
[in] The initial tracking ID.  

*source*    
Type: IVisualGestureBuilderFrameSource  
[out] The newly created frame source instance.  

<span id="ID4ES"></span>
#### Return value  

Type: HRESULT  
S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CreateVisualGestureBuilderFrameSource
RLTitle : CreateVisualGestureBuilderFrameSource
KeywordK : CreateVisualGestureBuilderFrameSource
KeywordF : CreateVisualGestureBuilderFrameSource
KeywordF : Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource(IKinectSensor,UINT64,IVisualGestureBuilderFrameSource@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource(IKinectSensor,UINT64,IVisualGestureBuilderFrameSource@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource(IKinectSensor,UINT64,IVisualGestureBuilderFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
