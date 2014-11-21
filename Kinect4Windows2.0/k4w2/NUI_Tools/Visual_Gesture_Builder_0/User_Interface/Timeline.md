Visual Gesture Builder Timeline  
===============================  

Describes the Timeline and Output panes.  
-   [Timeline Pane](#ID4EN)  
-   [Output Pane](#ID4EAC)  
-   [Keyboard Shortcuts](#ID4EFC)  

<span id="ID4EN"></span>

Timeline Pane  
=============  

Use the timeline to perform time tagging of clips.  

| ![](../../../../resources/note.gif)Note                                         |
|---------------------------------------------------------------------------------|
| The title of the **Timeline** pane changes based on the currently selected tag. |

<span id="ID4EY"></span>
Tagging Clips  
-------------  

For machine learning algorithms to train on clips, they must be tagged in some manner. Different machine language algorithms accept different types of tagging but, for a specific frame, some metadata representing the intended gesture is encoded. The following are the allowed tagging types.  

1.  In projects using [AdaBoostTrigger](../Detection_Technologies/AdaBoostTrigger.md), mark the range of frames where the gesture takes place. For each part of the clip, set the gesture tag boolean value to either true or false.  
2.  In projects using [RFRProgress](../Detection_Technologies/RFRProgress.md), mark key frames where the gesture takes place. For each part of the clip, set the gesture tag float value to a value that is indicative of the progress over the span of the gesture.  

**Figure 1.  Tagging Clips**  

![](../../../../resources/k4w_VisualGestureBuilder_Timeline.png)  
The following is an example of steps that you can perform to generate training data.  
1.  Click on one of the files. You are presented with the file view.  
2.  Scroll and select a represented frame.  
3.  Add new metadata.  
4.  Repeat the previous steps as many times as needed.  

<span id="ID4EAC"></span>

Output Pane  
===========  

This pane displays status and error messages. You can use the results of application operations that are displayed here for debugging purposes.  

<span id="ID4EFC"></span>

Keyboard Shortcuts  
==================  

The following keyboard shortcuts are available to expedite tagging gestures in VGB.  

| Keyboard Shortcut    | Description                                                                                                  |
|----------------------|--------------------------------------------------------------------------------------------------------------|
| LEFT Arrow           | Move the position marker to the previous frame.                                                              |
| RIGHT Arrow          | Move the position marker to the next frame.                                                                  |
| CTRL + LEFT          | Move the position marker to the previous key frame.                                                          |
| CTRL + RIGHT         | Move the position marker to the next key frame.                                                              |
| PAGEUP               | Load the tags for the previous gesture listed in the Tags pane.                                              |
| PAGEDOWN             | Load the tags for the next gesture listed in the Tags pane.                                                  |
| Shift + HOME         | Select all frames to the left of the position marker to the start of the file.                               |
| Shift + END          | Select all frames to the right of the position marker to the end of the file.                                |
| Shift + LEFT         | Select the frames to the left of the position marker.                                                        |
| Shift + RIGHT        | Select the frames to the right of the position marker.                                                       |
| CTRL + Shift + LEFT  | Select all frames left of the position marker to the previous key frame.                                     |
| CTRL + Shift + RIGHT | Select all frames right of the position marker to the next key frame.                                        |
| UP                   | Increase the value of the selected tag.                                                                      |
| DOWN                 | Decrease the value of the selected tag.                                                                      |
| Delete               | Delete the value of the selected tag.                                                                        |
| CTRL + Delete        | Delete the selected key frame.                                                                               |
| Enter                | Set the tag to the default maximum value (true for discrete gesture types, 1 for continuous gesture types).  |
| Space                | Set the tag to the default minimum value (false for discrete gesture types, 0 for continuous gesture types). |
| CTRL + Z             | Undo last tag change.                                                                                        |
| CTRL + Y             | Redo a previously undone tag.                                                                                |

<span id="ID4EDF"></span>

See also  
========  

[Visual Gesture Builder user interface](../User_Interface.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Timeline
RLTitle : Visual Gesture Builder Timeline
KeywordA : O:Microsoft.Kinect.tools.k4w_timeline_vgb
KeywordA : e74e9406-b89d-e90b-80bc-3489f2720014
KeywordK : Visual Gesture Builder Timeline
AssetID : e74e9406-b89d-e90b-80bc-3489f2720014
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
