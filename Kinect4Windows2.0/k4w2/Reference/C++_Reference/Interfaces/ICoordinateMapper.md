ICoordinateMapper Interface  
===========================  

Represents the mapper that provides translation services from one point type to another. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface ICoordinateMapper : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**ICoordinateMapper** has the following members.  

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
<td align="left"><a href="ICoordinateMapper/Methods/GetCoordinateMappingChan.md">GetCoordinateMappingChangedEventData</a></td>
<td align="left">Gets event data when the mapping between types of points changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/GetDepthCameraIntrinsics.md">GetDepthCameraIntrinsics</a></td>
<td align="left">Returns the calibration data for the depth camera.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/GetDepthFrameToCameraSpa.md">GetDepthFrameToCameraSpaceTable</a></td>
<td align="left">Generates a table of camera space points.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/MapCameraPointsToColorSp.md">MapCameraPointsToColorSpace</a></td>
<td align="left">Maps an array of points from camera space to color space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/MapCameraPointsToDepthSp.md">MapCameraPointsToDepthSpace</a></td>
<td align="left">Maps an array of points from camera space to depth space.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/MapCameraPointToColorSpace.md">MapCameraPointToColorSpace</a></td>
<td align="left">Maps a point from camera space to color space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/MapCameraPointToDepthSpace.md">MapCameraPointToDepthSpace</a></td>
<td align="left">Maps a point from camera space to depth space.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/MapColorFrameToCameraSpace.md">MapColorFrameToCameraSpace</a></td>
<td align="left">Uses the color frame data to map the entire frame from color space to camera space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/MapColorFrameToDepthSpace.md">MapColorFrameToDepthSpace</a></td>
<td align="left">Uses the depth frame data to map the entire frame from color space to depth space.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/MapDepthFrameToCameraSpace.md">MapDepthFrameToCameraSpace</a></td>
<td align="left">Uses the depth frame data to map the entire frame from depth space to camera space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/MapDepthFrameToColorSpace.md">MapDepthFrameToColorSpace</a></td>
<td align="left">Uses the depth frame data to map the entire frame from depth space to color space.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/MapDepthPointsToCameraSp.md">MapDepthPointsToCameraSpace</a></td>
<td align="left">Maps an array of points and depths from depth space to camera space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/MapDepthPointsToColorSpace.md">MapDepthPointsToColorSpace</a></td>
<td align="left">Maps an array of points and depths from depth space to color space.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/MapDepthPointToCameraSpace.md">MapDepthPointToCameraSpace</a></td>
<td align="left">Maps a point and depth from depth space to camera space.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/MapDepthPointToColorSpace.md">MapDepthPointToColorSpace</a></td>
<td align="left">Maps a point and depth from depth space to color space.</td>
</tr>
<tr class="even">
<td align="left"><a href="ICoordinateMapper/Methods/SubscribeCoordinateMappi.md">SubscribeCoordinateMappingChanged</a></td>
<td align="left">Subscribes to the specified event handler to process changes in coordinate mapping.</td>
</tr>
<tr class="odd">
<td align="left"><a href="ICoordinateMapper/Methods/UnsubscribeCoordinateMap.md">UnsubscribeCoordinateMappingChanged</a></td>
<td align="left">Unsubscribes the specified event handler from processing changes in coordinate mapping.</td>
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
TOCTitle : ICoordinateMapper Interface
RLTitle : ICoordinateMapper Interface
KeywordK : ICoordinateMapper interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : ICoordinateMapper
KeywordF : Microsoft.Kinect.kinect.ICoordinateMapper
KeywordA : T:Microsoft.Kinect.kinect.ICoordinateMapper
AssetID : T:Microsoft.Kinect.kinect.ICoordinateMapper
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ICoordinateMapper
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
