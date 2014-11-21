IAudioSource Interface  
======================  

Represents an audio frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IAudioSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioSource** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_AudioBeams_Method.md">get_AudioBeams</a></td>
<td align="left">Gets the audio beams.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/get_AudioCalibrationState.md">get_AudioCalibrationState</a></td>
<td align="left">Gets a value indicating whether the audio source needs to be calibrated. This API is not implemented in the Kinect for Windows v2 SDK and will always return Calibrated. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets the current activity status of this source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the parent sensor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_MaxSubFrameCount_Method.md">get_MaxSubFrameCount</a></td>
<td align="left">Gets the maximum number of sub frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/get_SubFrameDuration_Method.md">get_SubFrameDuration</a></td>
<td align="left">Returns the sub frame duration.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_SubFrameLengthInBytes.md">get_SubFrameLengthInBytes</a></td>
<td align="left">Returns the sub frame length (in bytes).</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">Retrieves the event data when a frame is captured.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Opens a new stream reader. This reader must be disposed.</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
<td align="left">Unsubscribes a subscribed event handler when a frame has been captured.</td>
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
TOCTitle : IAudioSource Interface
RLTitle : IAudioSource Interface
KeywordK : IAudioSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioSource
KeywordF : Microsoft.Kinect.kinect.IAudioSource
KeywordA : T:Microsoft.Kinect.kinect.IAudioSource
AssetID : T:Microsoft.Kinect.kinect.IAudioSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
