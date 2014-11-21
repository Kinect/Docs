Record View  
===========  

The record view contains the following controls:  

-   [Recording Controls](#ID4EY)  
-   [Recording Meter](#ID4EHC)  

**Figure 1.  Record view**  

![](../../../../resources/k4w_kinectstudio_recordview.png) <span id="ID4EY"></span>

Recording Controls  
==================  

These controls let you start and stop the recording of streams.  

| Control                                                       | Function         | Description                                   |
|---------------------------------------------------------------|------------------|-----------------------------------------------|
| ![](../../../../resources/k4w_kinectstudio_button_record.png) | Start recording. | Starts the recording of all selected streams. |
| ![](../../../../resources/k4w_kinectstudio_button_stop.png)   | Stop recording.  | Stops the recording of all streams.           |

| ![](../../../../resources/note.gif)Note                                                                        |
|----------------------------------------------------------------------------------------------------------------|
| Recording is disabled when one or more pre-conditions - such as inter-stream dependencies - are not satisfied. |

<span id="ID4EHC"></span>

Recording Meter  
===============  

When recording, the recording meter appears below the record controls. The meter tracks the available amount of memory buffer throughout the recording and lists the file name, file size and recording time. The buffer size is configurable under the [Kinect Studio Settings](../Kinect_Studio_Settings.md).  

| ![](../../../../resources/note.gif)Note                                                                                                                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| The file size listed as part of the recording meter is the count of bytes written to disk (excluding any buffered data). If the sensor is unplugged while recording, there is no data to capture, and you will see the recording time increase but the file size remains unchanged. |



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Record View
RLTitle : Record View
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_KinectStudio_recordview
KeywordA : 40367b3f-6983-97ff-c80d-57e0dc22ddeb
KeywordK : Record View
KeywordK : Kinect Studio, playing data
KeywordK : XEF files, recording
AssetID : 40367b3f-6983-97ff-c80d-57e0dc22ddeb
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
