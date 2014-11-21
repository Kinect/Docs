IAudioSource Methods  
====================  

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
<td align="left"><a href="Methods/get_AudioBeams_Method.md">get_AudioBeams</a></td>
<td align="left">Gets the audio beams.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/get_AudioCalibrationState.md">get_AudioCalibrationState</a></td>
<td align="left">Gets a value indicating whether the audio source needs to be calibrated. This API is not implemented in the Kinect for Windows v2 SDK and will always return Calibrated. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">Gets the current activity status of this source.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">Gets the parent sensor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/get_MaxSubFrameCount_Method.md">get_MaxSubFrameCount</a></td>
<td align="left">Gets the maximum number of sub frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/get_SubFrameDuration_Method.md">get_SubFrameDuration</a></td>
<td align="left">Returns the sub frame duration.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/get_SubFrameLengthInBytes.md">get_SubFrameLengthInBytes</a></td>
<td align="left">Returns the sub frame length (in bytes).</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">Retrieves the event data when a frame is captured.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Opens a new stream reader. This reader must be disposed.</td>
</tr>
<tr class="even">
<td align="left"><a href="Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">Event that is used to notify the application that the next frame is ready to be delivered to subscribed readers or if a frame has been dropped.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
<td align="left">Unsubscribes a subscribed event handler when a frame has been captured.</td>
</tr>
</tbody>
</table>



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IAudioSource Methods
RLTitle : IAudioSource Methods
KeywordK : IAudioSource interface, methods
KeywordA : Methods.T:Microsoft.Kinect.kinect.IAudioSource
AssetID : Methods.T:Microsoft.Kinect.kinect.IAudioSource
Locale : en-us
CommunityContent : 1
TargetOS : Windows
TopicType : kbSyntax
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
