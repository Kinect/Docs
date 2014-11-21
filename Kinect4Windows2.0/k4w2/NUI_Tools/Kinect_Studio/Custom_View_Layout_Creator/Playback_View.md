Playback View  
=============  

The playback view contains the following controls:  

-   [Playback Controls](#ID4EY)  
-   [Playback-Looping Controls](#ID4E6C)  
-   [Pause-Point Controls](#ID4EAE)  
-   [Metadata Controls](#ID4ESF)  
-   [Timeline Control](#ID4E1G)  
-   [Stream Selection Controls](#ID4EQAAC)  
-   [Stream Attribute Controls](#ID4ESDAC)  
-   [Target Stream Control](#ID4EIIAC)  
-   [Swim-lane Control](#ID4E2IAC)  

**Figure 1.  Playback View**  

![](../../../../resources/k4w_kinectstudio_playbackview.png) <span id="ID4EY"></span>

Playback Controls  
=================  

These controls let you connect or disconnect the Kinect Studio tool to/from the Kinect Studio Service.  

| Control                                                      | Function        | Description                                                                         |
|--------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------|
| ![](../../../../resources/k4w_kinectstudio_button_play.png)  | Start playback. | Starts the playback of all selected streams.                                        |
| ![](../../../../resources/k4w_kinectstudio_button_pause.png) | Pause playback. | Pauses the playback. The cursor remains at the last event played.                   |
| ![](../../../../resources/k4w_kinectstudio_button_stop.png)  | Stop playback.  | Stops the playback of all selected streams. The cursor resets to start of timeline. |
| ![](../../../../resources/k4w_kinectstudio_button_step.png)  | Step playback.  | Steps a single event in the file. Use when playback is stopped or paused.           |

<span id="ID4E6C"></span>

Playback-Looping Controls  
=========================  

Sometimes, it is desirable or necessary to loop the playback of a clip. Playback looping allows for the repeated playback of the same clip or range (as defined by the IN and OUT points). These controls let you specify the starting and ending iterations of looped playback.  

Stopping a playback resets the loop iteration counter back to zero; pausing/resuming a playback does not. If playback was accidentally stopped, the loop iteration counter can be manually set to a starting value before re-starting the playback.  

| Function       | Description                                               |
|----------------|-----------------------------------------------------------|
| Loop Count     | Displays or modifies the total number of loop iterations. |
| Loop Iteration | Displays or modifies the current loop iteration number.   |

<span id="ID4EAE"></span>

Pause-Point Controls  
====================  

Pause-points allow for the automatic suspension of a playback e.g. when you are debugging your application. These controls let you disable, enable, and delete all pause-points that are present on the timeline control.  

| Control                                                                   | Function                  |
|---------------------------------------------------------------------------|---------------------------|
| ![](../../../../resources/k4w_kinectstudio_button_disablepausepoints.png) | Disable all pause points. |
| ![](../../../../resources/k4w_kinectstudio_button_enablepausepoints.png)  | Enable all pause points.  |
| ![](../../../../resources/k4w_kinectstudio_button_deletepausepoints.png)  | Delete all pause points.  |

<span id="ID4ESF"></span>

Metadata Controls  
=================  

Metadata is data about data. File-level metadata contains data that applies to an entire clip (as opposed to stream-level metadata which applies to an individual stream). For information about how to add, modify, and remove metadata, see [Metadata View](Metadata_View.md).  

| Control                                                             | Function       | Description                                                          |
|---------------------------------------------------------------------|----------------|----------------------------------------------------------------------|
| ![](../../../../resources/k4w_kinectstudio_button_filemetadata.png) | File metadata. | Displays the file metadata in the [Metadata View](Metadata_View.md). |

<span id="ID4E1G"></span>

Timeline Control  
================  

![](../../../../resources/k4w_kinectstudio_timelinecontrol.png)  
The playback timeline ruler places all stream data in a temporal context. The timeline band above the timeline contains different timeline annotations: the IN and OUT points, pause-points and markers – in three horizontally lanes stacked atop each other.  

You can also right-click on the timeline band to adjust the annotations via the context-menu.  

![](../../../../resources/k4w_kinectstudio_timelinecontext1.png) <span id="ID4EIH"></span>
IN and OUT Points  
-----------------  

The IN and OUT points (red angled-brackets) let you specify the time range of the clip that is played back. Hovering over the IN or OUT point will display its timestamp. You can change the location/timestamp of the IN and OUT points by dragging them along the upper lane of the timeline band.  

![](../../../../resources/k4w_kinectstudio_timelinecontext2.png)  

<span id="ID4ESH"></span>
Pause Points  
------------  

Pause-points (red circles) let you automatically suspend playback at a given point in time.  

Place or remove a pause-point by clicking on the middle lane of the timeline band. Hovering over a pause-point will display its timestamp. You can adjust the location/timestamp of the pause-point by dragging the pause-point across the middle lane of the timeline band.  

![](../../../../resources/k4w_kinectstudio_timelinecontext3.png)  

<span id="ID4E5H"></span>
Markers  
-------  

Markers (blue squares) let you annotate a point in time with a name and optional custom metadata.  

Place a marker by clicking on the lower lane of the timeline band. Hovering over a marker will display its name and timestamp. You can adjust the location/timestamp of the marker by dragging the marker across the lower lane of the timeline band.  

Right-click to: edit the timestamp, edit the marker name, attach metadata, or delete the marker. You can also set a pause-point at the marker location. You can create a “coupled” pause-point (blue circles) based on a marker. Coupled pause-points share the same timestamp as the marker and are automatically adjusted when the marker is repositioned. You can also set the IN and OUT points based on the marker.  

![](../../../../resources/k4w_kinectstudio_timelinecontext4.png)  

| ![](../../../../resources/note.gif)Note                                                                                                                                                                                                                       |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pause-points (including coupled pause-points) are created locally on your machine. They are preserved across Kinect Studio sessions, but are not persisted in the XEF file. Markers and metadata are persisted in the XEF file and preserved across machines. |

<span id="ID4EQAAC"></span>

Stream Selection Controls  
=========================  

![](../../../../resources/k4w_kinectstudio_streamselectioncontrols.png)  
These controls, let you select which streams in the list of streams the operation applies to. You may also choose to show/hide streams that are irrelevant to your scenario to de-clutter the list of streams.  

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Control</th>
<th align="left">Function</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_deselectallstreams.png" /></td>
<td align="left">Deselect all streams.</td>
<td align="left">Clears the stream selection in the list of streams.</td>
</tr>
<tr class="even">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_showhiddenstreams.png" /></td>
<td align="left">Show ‘hidden’ streams.</td>
<td align="left">Displays all streams regardless of their visibility in the list of streams.</td>
</tr>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_hidehiddenstreams.png" /></td>
<td align="left">Hide ‘hidden’ streams.</td>
<td align="left">Hides all streams for which visibility is set to ‘hidden’ from the list of streams.</td>
</tr>
<tr class="even">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_showexpandedinfo.png" /></td>
<td align="left">Show expanded info for streams.</td>
<td align="left">Expands the stream attribute controls.</td>
</tr>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_hideexpandedinfo.png" /></td>
<td align="left">Hide expanded info for streams.</td>
<td align="left">Collapses the stream attribute controls.</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">Stream Count</td>
<td align="left">Lists the number of visible and hidden streams.</td>
</tr>
</tbody>
</table>

| ![](../../../../resources/note.gif)Note                            |
|--------------------------------------------------------------------|
| The stream selection can only be altered when playback is stopped. |

<span id="ID4ESDAC"></span>

Stream Attribute Controls  
=========================  

![](../../../../resources/k4w_kinectstudio_streamattributecontrols.png)  
When connected, each entry in the list of streams displays the selection and visibility state of the stream, followed by the stream name and a swim-lane control. The controls for each stream are:  

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Control</th>
<th align="left">Function</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_selectstream.png" /></td>
<td align="left">Stream selected.</td>
<td align="left">When connected, selects the stream.</td>
</tr>
<tr class="even">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_deselectstream.png" /></td>
<td align="left">Stream not selected.</td>
<td align="left">When connected, deselects the stream.</td>
</tr>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_settohidden.png" /></td>
<td align="left">Stream is visible in stream list.</td>
<td align="left">Sets the stream visibility to <strong>hidden</strong>.</td>
</tr>
<tr class="even">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_settovisible.png" /></td>
<td align="left">Stream is hidden from stream list.</td>
<td align="left">Sets the stream visibility to <strong>visible</strong>.</td>
</tr>
<tr class="odd">
<td align="left"></td>
<td align="left">Stream Name</td>
<td align="left">Displays the stream name.</td>
</tr>
</tbody>
</table>

When the stream attributes control is expanded, the following additional controls are available:  

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Control</th>
<th align="left">Function</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_filemetadata.png" /></td>
<td align="left">Stream metadata</td>
<td align="left">Displays the stream metadata in the <a href="Metadata_View.md">Metadata View</a>.</td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">Target stream</td>
<td align="left">Displays the active target stream mapping.</td>
</tr>
<tr class="odd">
<td align="left"></td>
<td align="left">Event Index</td>
<td align="left">Displays the event index or <strong>&lt;no selection&gt;</strong></td>
</tr>
<tr class="even">
<td align="left"></td>
<td align="left">Frame</td>
<td align="left">Displays the frame number for image-based streams.</td>
</tr>
</tbody>
</table>

<span id="ID4EIIAC"></span>

Target Stream Control  
=====================  

When connected, this control lists the selected target-stream to which the file-stream can be mapped for playback. The target-stream represents the NUI client end-point to which stream data is delivered before it is passed to your application.  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><img src="../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Wherever possible, Kinect Studio will automatically map the file-stream to the matching target-stream.</p>
<p>When a stream – such as Nui Body Index - is present in the XEF file, the stream is visible for inspection but cannot be played back. In this case, there is no available target stream to which to map the file stream.</p>
<p>In advanced scenarios, where multiple instances of a stream type are present in a XEF file, the target stream control lets you map the appropriate stream instance to the target-stream.</p></td>
</tr>
</tbody>
</table>

![](../../../../resources/k4w_kinectstudio_targetstreamcontrol.png)  

<span id="ID4E2IAC"></span>

Swim-lane Control  
=================  

The swim-lane control displays ticks, timing, frame, and event information for the events in the stream across the timeline indicated by the timeline control ruler. A cursor in the swim-lanes tracks the current playback position. When playback is paused or stopped, you can click on the swim-lane to change the current playback position. Hovering over the swim-lane will display the event-index, frame number and start timestamp for the tick under the cursor.  

![](../../../../resources/k4w_kinectstudio_swimlane.png)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Playback View
RLTitle : Playback View
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_KinectStudio_playbackview
KeywordA : f40d34d5-e160-bad8-97ed-f88464ac5fbc
KeywordK : Playback View
KeywordK : Kinect Studio, playback view
KeywordK : XEF files, playing
AssetID : f40d34d5-e160-bad8-97ed-f88464ac5fbc
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
