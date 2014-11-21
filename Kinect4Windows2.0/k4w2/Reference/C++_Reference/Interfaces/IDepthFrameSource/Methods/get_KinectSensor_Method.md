IDepthFrameSource::get\_KinectSensor Method  
===========================================  

Gets the Kinect sensor object of the depth frame source. <span id="syntaxSection"></span>

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
HRESULT get_KinectSensor(  
         IKinectSensor **sensor  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sensor*    
Type: IKinectSensor  
[out] The Kinect sensor object of the depth frame source.  

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
TOCTitle : get_KinectSensor Method
RLTitle : IDepthFrameSource::get_KinectSensor Method
KeywordK : get_KinectSensor method
KeywordK : IDepthFrameSource::get_KinectSensor method
KeywordF : IDepthFrameSource::get_KinectSensor
KeywordF : get_KinectSensor
KeywordF : Microsoft.Kinect.kinect.IDepthFrameSource.get_KinectSensor(IKinectSensor@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrameSource.get_KinectSensor(IKinectSensor@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrameSource.get_KinectSensor(IKinectSensor@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameSource::get_KinectSensor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
