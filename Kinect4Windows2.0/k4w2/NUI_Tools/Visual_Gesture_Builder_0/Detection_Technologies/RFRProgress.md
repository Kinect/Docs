RFRProgress  
===========  

RFRProgress is a detection technology that produces an analog or continuous result. It uses the Random Forest Regression (RFR) machine learning algorithm to determine the progress of a gesture performed by a user. It uses tagging models that are represented by analog signals that occur during a gesture.  

Examples of these models could be an abstract concept such as the "progress" of a gesture or a quantifiable value such as the angle of an arm in a baseball pitch. Valid ranges for the RFRProgress tags are based on the model that the analog signal represents.  

The input is an analog signal that models an action as progress during a gesture. For example, the position of the arm in a golf swing.  

The RFRProgress is a *context*-based detector, meaning that the progress detection is only valid when a user is performing a gesture. The progress detection can be enabled as follows:  

1.  When the application is aware that the user is performing a gesture, it enables the detection and uses it to aid in rendering a simulation.  
2.  Progress detection is enabled when a discrete gesture (AdaBoostTrigger) is detected.  

| ![](../../../../resources/note.gif)Note                                              |
|--------------------------------------------------------------------------------------|
| You can override the RFRProgress project settings in the solution's global settings. |

| ![](../../../../resources/note.gif)Note                                                                                                                                                                                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| When using RFRProgress, you must include the vgbtechs\\RFRProgressTech.dll runtime component with your application. For more information, see [Visual Gesture Builder Headers, Libraries, and Assemblies](../Headers_Libraries_and.md). |

-   [Input Parameters](#ID4EGB)  
-   [Run Time Data](#ID4E4G)  
-   [Remarks](#ID4EJH)  

<span id="ID4EGB"></span>

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
<th align="left">Parameter Name</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Use Rotation Variant Feature</td>
<td align="left">BOOL</td>
<td align="left"><p>When set to <strong>true</strong>, the gesture detection will take into account the user’s global rotation. In this case, the detection produces a stronger signal that is less robust to orientation change. When set to <strong>false</strong>, gesture detection will try to ignore global rotation as much as possible. For example, golf swing with the user head on and golf swing with the user at 45 degrees returns a similar signal.</p></td>
</tr>
<tr class="even">
<td align="left">Number of Trees</td>
<td align="left">INT</td>
<td align="left"><p>This parameter affects the accuracy, memory, and disk space. Larger values give better results at the cost of more memory and disk space, and also increases run time CPU use for searching through these trees.</p></td>
</tr>
<tr class="odd">
<td align="left">Maximum Tree Depth</td>
<td align="left">INT</td>
<td align="left"><p>This parameter controls the maximal complexity of a decision tree. Larger values allow a tree to grow deeper for complex scenarios, at the cost of more memory space and CPU use.</p></td>
</tr>
<tr class="even">
<td align="left">Cluster Threshold</td>
<td align="left">FLOAT</td>
<td align="left"><p>The lower this value is, the less change can occur from frame to frame. This could produce better overall results; however, there will be more misdetections.</p>
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">A smaller value means a more localized search, which could be more accurate if the search is performed in the correct neighborhood. But the search could also be &quot;stuck&quot; in a neighborhood when no good match could be found.</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="odd">
<td align="left">Weight Factor</td>
<td align="left">FLOAT</td>
<td align="left">The weight of the output from the previous frame that will affect the current frame’s output. 0 means no effect at all.</td>
</tr>
<tr class="even">
<td align="left">Use Hands Data</td>
<td align="left">BOOL</td>
<td align="left"><p>Default to false. This means that by default the hand states are not used for training and detection. For training and detection to use the hand states, set this property to true.</p>
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../resources/caution.gif" />Caution</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Hands data is only available for up to two users. If your game supports more than two simultaneous users, you should not use hands data during gesture training.</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="odd">
<td align="left">Ignore Left Arm</td>
<td align="left">BOOL</td>
<td align="left"><p>Default to false. This means that by default the following left-arm joints are used for training.</p>
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
<td align="left"><p>Default to false. This means that by default the following right-arm joints are used for training.</p>
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
<td align="left"><p>Default to false. This means that by default the following lower-body joints are used for training.</p>
<ul>
<li>knees</li>
<li>ankles</li>
<li>feet</li>
</ul>
<p>For training to ignore the lower-body joints, set this property to true. This is useful when you train a gesture that uses upper body only and when you want a gesture to be applicable for both seated and standing positions.</p></td>
</tr>
</tbody>
</table>

<span id="ID4E4G"></span>

Run Time Data  
=============  

An RFRProgress gesture will be represented as a **ContinuousGestureResult** class during runtime. The **ContinuousGestureResult** should be used to check the progress value for the gesture.  

<span id="ID4EJH"></span>

Remarks  
=======  

RFRProgress is a continuous gesture, which means that, unless it is disabled, it will always provide a progress value even when the user is not performing the gesture. The simplest way to know when the progress result is valid, is for your application to use a discrete gesture (AdaBoostTrigger) to help determine context.  

For example, when the first frame is detected for the discrete gesture (Jump), enable the continuous gesture (JumpProgress). When the progress for the continuous gesture reaches a complete value, and/or the discrete gesture (Jump) is no longer detected, disable the continuous gesture (JumpProgress) so that it will no longer use resources while it is invalid.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : RFRProgress
RLTitle : RFRProgress
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_VisualGestureBuilder_RfrProgress
KeywordA : 100e82ae-dc3d-e5fb-2796-797431bd6114
KeywordK : RFRProgress
AssetID : 100e82ae-dc3d-e5fb-2796-797431bd6114
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
