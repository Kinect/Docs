CreateHighDefinitionFaceFrameSource  
===================================  

Creates a high definition face frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateHighDefinitionFaceFrameSource(  
         IKinectSensor *sensor,  
         IHighDefinitionFaceFrameSource **hdFaceFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sensor*    
Type: IKinectSensor  
[in] The kinect sensor from which the source should be created.  

*hdFaceFrameSource*    
Type: IHighDefinitionFaceFrameSource  
[out] The high definition face frame source.  

<span id="ID4EN"></span>
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
TOCTitle : CreateHighDefinitionFaceFrameSource
RLTitle : CreateHighDefinitionFaceFrameSource
KeywordK : CreateHighDefinitionFaceFrameSource
KeywordF : CreateHighDefinitionFaceFrameSource
KeywordF : Microsoft.Kinect.face.CreateHighDefinitionFaceFrameSource(IKinectSensor,IHighDefinitionFaceFrameSource@)
KeywordA : M:Microsoft.Kinect.face.CreateHighDefinitionFaceFrameSource(IKinectSensor,IHighDefinitionFaceFrameSource@)
AssetID : M:Microsoft.Kinect.face.CreateHighDefinitionFaceFrameSource(IKinectSensor,IHighDefinitionFaceFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.CreateHighDefinitionFaceFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
