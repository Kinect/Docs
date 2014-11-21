Visual Gesture Builder Training Project  
=======================================  

Describes the Training Project in Visual Gesture Builder.  
-   [Training Project Menu](#ID4EN)  
-   [Training Project Settings](#ID4E2C)  
-   [Training Project Results](#ID4EJG)  

<span id="ID4EN"></span>

Training Project Menu  
=====================  

To access the context menu for a training project, open an existing solution in VGB (**File \> Open Solution**), and right-click on a gesture project in the **Explorer**.  

The **Training Project** menu displays options for adding clips and building the gesture detector.  

**Figure 1.  Training Project Menu**  

![](../../../../resources/k4w_vgb_training_project_menu.png)  
The following options are available for the training project.  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Menu Option</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Add Clip</td>
<td align="left">Adds one or more clips (.xef) to the project. This will create an associated .vgbclip file for the tagging metadata, if no such file exists.</td>
</tr>
<tr class="even">
<td align="left">Build</td>
<td align="left"><p>Builds the gesture database file (.gba). This trains the gesture detector and outputs a single project database (.gba), which can only be used for analysis or <strong>Live Preview</strong> testing.</p>
<p>This option is disabled when another build or analysis is in progress.</p></td>
</tr>
<tr class="odd">
<td align="left">Save</td>
<td align="left">Saves all changes to the project (.vgbproj), including clip references.</td>
</tr>
<tr class="even">
<td align="left">Remove</td>
<td align="left">Removes the project from the solution.</td>
</tr>
<tr class="odd">
<td align="left">Live Preview...</td>
<td align="left">Launches VGBView with the selected gesture database.</td>
</tr>
</tbody>
</table>

<span id="ID4E2C"></span>

Training Project Settings  
=========================  

The training project settings enable you to modify project property values. These values affect gesture training results and performance. The settings that are available depend on the detection technology that is used by the selected gesture project. For more information, see [Detection Technologies](../Detection_Technologies.md).  

**Figure 2.  Training Project Settings**  

![](../../../../resources/k4w_vgb_training_project_settings.png)  
<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Parameter</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Name</td>
<td align="left"><p>Settings property name. The names listed depend on the detection technology used by the project.</p>
<ul>
<li>Use Hands Data: When set to true, VGB uses hand states to train and detect gestures.</li>
<li>Ignore Left Arm: When set to true, VGB ignores left arm joints (elbow, wrist, hand, hand tip, thumb) to train and detect gestures.</li>
<li>Ignore Right Arm: When set to true, VGB ignores right arm joints (elbow, wrist, hand, hand tip, thumb) to train and detect gestures.</li>
<li>Ignore Lower Body: When set to true, VGB ignores leg joints (knees, ankles, feet) to train and detect gestures.</li>
</ul></td>
</tr>
<tr class="even">
<td align="left">Value</td>
<td align="left">Assigns the value to the settings property.</td>
</tr>
<tr class="odd">
<td align="left">Type</td>
<td align="left">Displays the type associated with the settings property.</td>
</tr>
<tr class="even">
<td align="left">Export</td>
<td align="left"><p>Export the project property values to a file. Use this control as follows:</p>
<ul>
<li>Click the <strong>Export</strong> button. The Save As dialog window is displayed.</li>
<li>In the <strong>File name</strong>: box, enter the name to use for the file. If the project name is &quot;GolfSwing&quot;, the default file name is &quot;GolfSwing.fid&quot;.</li>
</ul></td>
</tr>
<tr class="odd">
<td align="left">Import</td>
<td align="left"><p>Import the project property values from a settings file (.fid) that you select. Use this control as follows:</p>
<ul>
<li>Click the <strong>Import</strong> button to display the <strong>Open</strong> dialog.</li>
<li>Enter the filename in the <strong>File name:</strong> box (such as &quot;GolfSwing.fid&quot;).</li>
</ul></td>
</tr>
</tbody>
</table>

<span id="ID4EJG"></span>

Training Project Results  
========================  

While building, training progress will be displayed in the **Output** pane for a gesture project. When complete, the resulting database (.gba) can then be loaded in **VgbView** on the computer for live testing (**File \> Live Preview**), or it can be used to analyze the gesture detector against a collection of test clips. For more information, see **Analysis Project**.  

<span id="ID4EZG"></span>

See also  
========  

[Visual Gesture Builder user interface](../User_Interface.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Training Project
RLTitle : Visual Gesture Builder Training Project
KeywordA : O:Microsoft.Kinect.tools.k4w_trainingproject_vgb
KeywordA : 0797825a-811a-57d9-7cbe-eb2c2e01866c
KeywordK : Visual Gesture Builder Training Project
AssetID : 0797825a-811a-57d9-7cbe-eb2c2e01866c
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
