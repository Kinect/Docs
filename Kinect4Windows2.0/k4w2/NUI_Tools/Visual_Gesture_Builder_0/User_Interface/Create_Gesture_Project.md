Create Gesture Project  
======================  

To create a new gesture for your collection, set focus to the solution node in the **Explorer** and then select **File \> Create New Project** or right-click on the solution and select **Create New Projec**t from the context menu.  

VGB contains a simple dialog to help with gesture creation. Specify the tag name, body side, detection technology, and common training settings for each gesture that you create.  

**Figure 1.  Create Gesture Project dialog**  

![](../../../../resources/k4w_gesture_project_create.png)  
<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Gesture Item</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Gesture Name</td>
<td align="left"><p>The name of the gesture tag. This name should be descriptive enough to capture the intent of the action. If your gesture corresponds to a particular side (Left vs Right) do not include “Left” or “Right” in the tag name, as that will be appended later when you select a Body Side.</p>
<p>Examples: Jump, Punch, Kick, Sit, FireWeapon, etc.</p></td>
</tr>
<tr class="even">
<td align="left">Body Side</td>
<td align="left"><p>Indicates which side of the body the gesture corresponds to. If Left is selected, &quot;_Left&quot; will be appended to the gesture name. If Right is selected &quot;_Right&quot; will be appended to the gesture name.</p>
<p>Options:</p>
<ul>
<li><strong>Any</strong> – The gesture is symmetrical and/or depends on both sides of the body (ex: Flap, Glide).</li>
<li><strong>Left</strong> – The gesture depends predominantly on the motion/position of the left leg or left arm (ex: Kick_Left, Punch_Left).</li>
<li><strong>Right</strong> – The gesture depends predominantly on the motion/position of the right leg or right arm (ex: Kick_Right, Punch_Right).</li>
</ul></td>
</tr>
<tr class="odd">
<td align="left">Gesture Type</td>
<td align="left"><p>Indicates which detection technology to use for gesture training and detection.</p>
<p>Options:</p>
<ul>
<li><strong>AdaBoostTrigger</strong> – This is a discrete gesture type. Boolean values of true/false are used to indicate when the gesture is occurring.</li>
<li><strong>RFRProgress</strong> – This is a continuous gesture type. Float values are assigned to indicate the progress of the user as they perform the gesture.</li>
</ul></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Training Setting</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Duplicate and Mirror Data During Training</td>
<td align="left"><p>If set to true (default value), all data for the gesture will be duplicated and mirrored during training. If data exists for the opposite body side (Left vs. Right), that data will also be mirrored and used during training.</p>
<p>Set to false if your gesture requires motion from both sides of the body (Body Side = Any) and the gesture is asymmetrical. For example, if the gesture requires that the right arm be up while the left arm is down.</p></td>
</tr>
<tr class="even">
<td align="left">Use Hands</td>
<td align="left"><p>If set to true, supported hand states (open/closed/lasso) will be used during training and detection.</p>
<p>Warning: Do not use this option if your application supports more than two simultaneous users.</p></td>
</tr>
<tr class="odd">
<td align="left">Ignore Left Arm</td>
<td align="left"><p>If set to true, all joints in the left arm will be ignored during training and detection.</p>
<p>Set to true if your gesture does not depend on motion/position of the left arm (Punch_Right, Push_Right, Kick, etc.).</p></td>
</tr>
<tr class="even">
<td align="left">Ignore Right Arm</td>
<td align="left"><p>If set to true, all joints in the right arm will be ignored during training and detection.</p>
<p>Set to true if your gesture does not depend on motion/position of the right arm (Punch_Left, Push_Left, Kick, etc.).</p></td>
</tr>
<tr class="odd">
<td align="left">Ignore Lower Body</td>
<td align="left"><p>If set to true, all joints below the hip region will be ignored during training and detection.</p>
<p>Set to True if your gesture does not depend on motion/position of the lower body. Such a gesture can usually be performed while seated or standing.</p></td>
</tr>
</tbody>
</table>

The joint mask is displayed on the right of the Training Settings. Toggling the Use/Ignore settings will update the joint mask. Green joints will be used during training and detection, and grey joints will be ignored. A blue circle around the hand indicates if hand state will be used.  

**Figure 2.  A right arm gesture**  

![](../../../../resources/k4w_gesture_project_training.png)  
When you are ready to create your gesture, select the **Confirm** button and save to the gesture to the desired location. The new gesture projects (both training and analysis), and will then appear in the **Explorer**.  

If you are confused about any of the options on the **Create Gesture Project** dialog, try using the **Gesture Wizard** link which is available at the top of the dialog. This will launch the [Gesture Wizard](Gesture_Wizard.md) tool, which will guide you step-by-step through the gesture creation process.  

<span id="ID4EEG"></span>

See also  
========  

[Visual Gesture Builder user interface](../User_Interface.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Create Gesture Project
RLTitle : Create Gesture Project
KeywordA : O:Microsoft.Kinect.tools.k4w_gesture_project
KeywordA : 815d2d93-0733-575b-18b4-b183d24ae2fc
KeywordK : Create Gesture Project
AssetID : 815d2d93-0733-575b-18b4-b183d24ae2fc
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
