AdaBoostTrigger  
===============  

The AdaBoostTrigger is a detection technology that produces a binary or discrete result. It uses an Adaptive Boosting (AdaBoost) machine learning algorithm to determine when a user performs a certain gesture.  

During training time it accepts input tags, **boolean** values, which mark the occurrence of a gesture, such as a hit. This marking or tagging is used to evaluate whether or not a gesture has happened and determines the confidence value of the event.  

| ![](../../../../resources/note.gif)Note                                                |
|----------------------------------------------------------------------------------------|
| You can override the AdaBoostTrigger project settings in the solution global settings. |

| ![](../../../../resources/note.gif)Note                                                                                                                                                                                                  |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| When using AdaBoostTrigger, you must include the vgbtechs\\AdaBoostTech.dll runtime component with your application. For more information, see [Visual Gesture Builder Headers, Libraries, and Assemblies](../Headers_Libraries_and.md). |

-   [Input Parameters](#ID4E2)  
-   [Run Time Data](##runtime_data)  

<span id="ID4E2"></span>

Input Parameters  
================  

The following table describes the input parameters that you can use when tagging a gesture. You enter these parameters in the **Project Settings** grid, as shown in the [Visual Gesture Builder Training Project](../User_Interface/Training_Project.md).  

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Property Name</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Accuracy Level</td>
<td align="left">FLOAT</td>
<td align="left"><p>A floating point value in the range [0..1].</p>
<p>This value controls how accurate your results are, but also affects the training time. The higher the accuracy, the longer the training time. As a guideline you can use the following values:</p>
<ul>
<li>Retail Build – 0.98.</li>
<li>Release Build – 0.95.</li>
<li>Quick Experiment – 0.8.</li>
</ul></td>
</tr>
<tr class="even">
<td align="left">Number of Weak Classifiers at Run Time</td>
<td align="left">INT</td>
<td align="left">The algorithm can potentially generate tens of thousands of weak classifiers. Using all of them will increase accuracy, but at the higher CPU cost on the computer. To use all the classifiers generated, use a value of 0.  
<p>The CPU cost for 1000 weak classifiers is only 25 microseconds and the results have more than adequate accuracy.</p></td>
</tr>
<tr class="odd">
<td align="left">Filter Results</td>
<td align="left">BOOL</td>
<td align="left"><p>The results of the algorithm are based on a frame, not on a gesture. A filter needs to be applied on the raw per frame results. The AdaBoostTrigger provides a simple low latency filter, but you have the option of disabling filtering and applying your own filter at run time on the computer.</p>
<p>The filter used is a simple sliding window of N frames, summing up the results and comparing it against a threshold value. The number of frames can be seen as a frequency and the threshold can be seen as amplitude.</p></td>
</tr>
<tr class="even">
<td align="left">Auto Find Best Filtering Params</td>
<td align="left">BOOL</td>
<td align="left">When filtering is switched on, you have the option to let the trainer automatically find best filtering parameters which will minimize the rate of false positives and false negatives.</td>
</tr>
<tr class="odd">
<td align="left">Weight Of False Positives During Auto Find</td>
<td align="left">FLOAT</td>
<td align="left"><p>A value in the range of [0..1] which is used when automatically finding the best filtering parameters.</p>
<p>If it is more important to reduce false positives, use a higher value. If it is more important to reduce false negatives, use a lower value.</p></td>
</tr>
<tr class="even">
<td align="left">Manual Filter Params: Number of Frames To Filter</td>
<td align="left">INT</td>
<td align="left"><p>A value in the range of [1..10].</p>
<p>You can choose the number of frames over which to filter if you do not choose to find the best filtering parameters automatically.</p></td>
</tr>
<tr class="odd">
<td align="left">Manual Filter Params: Threshold</td>
<td align="left">FLOAT</td>
<td align="left"><p>A value in the range of [0..1].</p>
<p>Lower values could increase true positives, at the risk of increasing false positives.</p>
<p>Higher values could decrease false positives, at the risk of decreasing true positives.</p></td>
</tr>
<tr class="even">
<td align="left">Duplicate And Mirror Data During Training</td>
<td align="left">BOOL</td>
<td align="left">Body data can be duplicated and mirrored in order to have a larger set of training data.</td>
</tr>
<tr class="odd">
<td align="left">% CPU For Training</td>
<td align="left">INT</td>
<td align="left">A value in the range of [0..100] which indicates the percentage of CPU resources that the trainer should use for training.</td>
</tr>
<tr class="even">
<td align="left">Use Hands Data</td>
<td align="left">BOOL</td>
<td align="left"><p>Default to false. This means by default the hand states are not used for training and detection. For training and detection to use the hand states, set this property to true.</p>
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Hands data is only available for up to two users. If your application supports more than two simultaneous users, you should not use hands data during gesture training.</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="odd">
<td align="left">Ignore Left Arm</td>
<td align="left">BOOL</td>
<td align="left"><p>Default to false. This means by default the following left-arm joints are used for training.</p>
<ul>
<li>elbow</li>
<li>wrist</li>
<li>hand</li>
<li>hand tip</li>
<li>thumb</li>
</ul>
<p>For training to ignore the left-arm joints, set this property to true. This is useful when you train a right-hand gesture and when the signals from the left hand need to be ignored.</p></td>
</tr>
<tr class="even">
<td align="left">Ignore Right Arm</td>
<td align="left">BOOL</td>
<td align="left"><p>Default to false. This means by default the following right-arm joints are used for training.</p>
<ul>
<li>elbow</li>
<li>wrist</li>
<li>hand</li>
<li>hand tip</li>
<li>thumb</li>
</ul>
<p>For training to ignore the right-arm joints, set this property to true. This is useful when you train a left-hand gesture and when the signals from the right hand need to be ignored.</p></td>
</tr>
<tr class="odd">
<td align="left">Ignore Lower Body</td>
<td align="left">BOOL</td>
<td align="left"><p>Default to false. This means by default the following lower-body joints are used for training.</p>
<ul>
<li>knees</li>
<li>ankles</li>
<li>feet</li>
</ul>
<p>For training to ignore the lower-body joints, set this property to true. This is useful when you train a gesture that uses upper body only and when you want a gesture to be applicable for both seated and standing positions.</p></td>
</tr>
</tbody>
</table>

<span id="#runtime_data"></span>

Run Time Data  
=============  

An AdaBoostTrigger gesture will be represented as a **DiscreteGestureResult** at run time. The **DiscreteGestureResult** should be used to check if the gesture has been detected and at what confidence.  

<span id="remarks"></span>

Remarks  
=======  

In training, if you only tag positive frames, AdaBoostTrigger uses all frames by default. The frames not tagged are used as negative frames. This generates a big training set, if the clips are very long.  

In training, if you intend to use only some frame ranges, instead of all the frames of a clip, you can explicitly tag negative frames. During training, the tool detects these explicitly tagged negative frames and ignores the non-tagged frames.  

The tool UI is designed to help you convert from implicit negative to explicit negative tagging.  

When you select a range of frames and set its value to **FALSE**, if there are non-tagged frames (gap) in the range, only those non-tagged are set to **FALSE**. All other existing tagged frames are not affected.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AdaBoostTrigger
RLTitle : AdaBoostTrigger
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_VisualGestureBuilder_AdaBoostTrigger
KeywordA : da5d2fe5-4e55-254a-261d-1e3cf1bed543
KeywordK : AdaBoostTrigger
AssetID : da5d2fe5-4e55-254a-261d-1e3cf1bed543
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
