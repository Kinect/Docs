Monitor View  
============  

The monitor view contains the following controls:  

-   [Monitoring Controls](#ID4EY)  
-   [Stream Selection Controls](#ID4EFC)  
-   [Stream Attribute Controls](#ID4EKE)  

**Figure 1.  Monitor view**  

![](../../../../resources/k4w_kinectstudio_monitorview.png) <span id="ID4EY"></span>

Monitoring Controls  
===================  

These controls let you connect or disconnect the Kinect Studio tool to/from the Kinect Studio Service.  

| Control                                                               | Function          | Description                                                                                                                            |
|-----------------------------------------------------------------------|-------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| ![](../../../../resources/k4w_kinectstudio_startmonitoring.png)       | Start monitoring. | Starts the monitoring of all selected streams. Data from the selected streams is visible in the Monitoring 2D and Monitoring 3D views. |
| ![](../../../../resources/k4w_kinectstudio_button_stopmonitoring.png) | Stop monitoring.  | Stops the monitoring of all streams.                                                                                                   |

<span id="ID4EFC"></span>

Stream Selection Controls  
=========================  

These controls let you select which streams in the list of streams the operation applies to. You may also choose to show/hide streams that are irrelevant to your scenario to de-clutter the list of streams.  

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
<td align="left"></td>
<td align="left">Stream Count</td>
<td align="left">Lists the number of visible and hidden streams.</td>
</tr>
</tbody>
</table>

| ![](../../../../resources/note.gif)Note                              |
|----------------------------------------------------------------------|
| The stream selection can only be altered when monitoring is stopped. |

<span id="ID4EKE"></span>

Stream Attribute Controls  
=========================  

When connected, each entry in the list of streams displays the selection and visibility state of the stream followed by the stream name. The controls for each stream are:  

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
<td align="left">Selects the stream.</td>
</tr>
<tr class="even">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_deselectstream.png" /></td>
<td align="left">Stream not selected.</td>
<td align="left">Deselects the stream.</td>
</tr>
<tr class="odd">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_settohidden.png" /></td>
<td align="left">Stream is visible in stream list.</td>
<td align="left">Sets the stream visibility to ‘hidden’.</td>
</tr>
<tr class="even">
<td align="left"><img src="../../../../resources/k4w_kinectstudio_button_settovisible.png" /></td>
<td align="left">Stream is hidden from stream list.</td>
<td align="left">Sets the stream visibility to ‘visible’.</td>
</tr>
<tr class="odd">
<td align="left"></td>
<td align="left">Stream Name</td>
<td align="left">Displays the stream name.</td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><img src="../../../../resources/note.gif" />Important</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Streams may depend on one or more other streams.</p>
<p>For example, while the Nui Body Frame data can be monitored and recorded for debugging/inspection purposes, it cannot be played back. To ‘playback’ a Nui Body Frame stream, you must playback the Nui IR and Nui Depth streams as the Nui Body Frame is re-derived from these streams.</p>
<p>When selecting a stream that has dependencies – such as the Nui IR, Kinect Studio will attempt to satisfy the inter-stream dependencies by automatically selecting the Nui Depth stream.</p>
<p>If you manually override a stream selection, and the stream dependencies are no longer satisfied, you may not be able to proceed with the desired operation until all stream dependency constraints are satisfied. You may inspect the stream dependencies by hovering over the stream name in the list of streams.</p>
<p>Using the Kinect Studio APIs, it possible to create multiple stream instances of various stream types. When hovering over the stream name in the streams list, the internal stream identifiers (stream type GUID ‘:’ stream instance GUID) are displayed in addition to the stream name, this helps to differentiate stream instances.</p>
<p><strong>Figure 2.  Stream Dependency and Identifiers</strong></p>
<img src="../../../../resources/k4w_kinectstudio_streamdependency.png" /></td>
</tr>
</tbody>
</table>



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Monitor View
RLTitle : Monitor View
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_KinectStudio_monitorview
KeywordA : e65150da-1c85-cbe8-cd19-3405ba171674
KeywordK : Monitor View
KeywordK : Kinect Studio, monitoring data
KeywordK : XEF files, playing
AssetID : e65150da-1c85-cbe8-cd19-3405ba171674
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
