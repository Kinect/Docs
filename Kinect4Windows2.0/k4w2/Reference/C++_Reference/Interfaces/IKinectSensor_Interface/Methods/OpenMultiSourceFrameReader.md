IKinectSensor::OpenMultiSourceFrameReader Method  
================================================  

Opens a new stream reader. <span id="syntaxSection"></span>

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
HRESULT OpenMultiSourceFrameReader(  
         DWORD enabledFrameSourceTypes,  
         IMultiSourceFrameReader **multiSourceFrameReader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*enabledFrameSourceTypes*    
Type: DWORD  
The frame source types.  

*multiSourceFrameReader*    
Type: IMultiSourceFrameReader  
[out] When this method returns, the new stream reader.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The *enabledFrameSourceTypes* can be one or more of the following values:  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Value</th>
<th align="left">Meaning</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">FrameSourceTypes::Color</td>
<td align="left">Include Color Frames in this MultiSourceFrameReader.  
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">MultiSourceFrameReader will align to the slowest framerate of any subscribed source. In lowlight scenarios, the color stream may drop to 15 FPS. If this happens, and MultiSourceFrameReader is subscribed to color as one of its subscribed sources, the rate of delivered frames will drop to 15 FPS for the entire instance of this MultiSourceFrameReader</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes_Infrared</td>
<td align="left">Include infrared frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes_Audio</td>
<td align="left">Audio is not supported for MultiSourceFrameReader. Including this source will cause this method to fail.</td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes_LongExposureInfrared</td>
<td align="left">Include long exposure infrared frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes_Depth</td>
<td align="left">Include depth frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes_BodyIndex</td>
<td align="left">Include body index frames in this MultiSourceFrameReader.</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes_Body</td>
<td align="left">Include body frames in this MultiSourceFrameReader.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenMultiSourceFrameReader Method
RLTitle : IKinectSensor::OpenMultiSourceFrameReader Method
KeywordK : OpenMultiSourceFrameReader method
KeywordK : IKinectSensor::OpenMultiSourceFrameReader method
KeywordF : IKinectSensor::OpenMultiSourceFrameReader
KeywordF : OpenMultiSourceFrameReader
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.OpenMultiSourceFrameReader(DWORD,IMultiSourceFrameReader@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.OpenMultiSourceFrameReader(DWORD,IMultiSourceFrameReader@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.OpenMultiSourceFrameReader(DWORD,IMultiSourceFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::OpenMultiSourceFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
