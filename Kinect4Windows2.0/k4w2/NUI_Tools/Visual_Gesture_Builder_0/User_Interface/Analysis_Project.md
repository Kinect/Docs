Visual Gesture Builder Analysis Project  
=======================================  

Describes the Analysis Project in Visual Gesture Builder.  
-   [Analysis Project Menu](#ID4EN)  
-   [Analysis Project Settings](#ID4EAD)  
-   [Analysis Project Results](#ID4EVG)  

<span id="ID4EN"></span>

Analysis Project Menu  
=====================  

To access the context menu for an analysis project, open an existing solution in VGB (**File \> Open Solution**) and right-click on an analysis gesture project (.a) in the **Explorer**.  

The **Analysis Project** menu displays options for adding clips and analyzing the gesture detector.  

**Figure 1.  Analysis Project menu**  

![](../../../../resources/k4w_vgb_analysis_project_menu.png)  
The following options are available for the analysis project.  

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
<td align="left">Adds one or more clips (.xef) to the project.</td>
</tr>
<tr class="even">
<td align="left">Analyze</td>
<td align="left"><p>Enables you to test a gesture database (.gba or .gbd) using all of the clips in the analysis project. Analyzes how well the detector results of the analysis clips compare to the tags on the clips in the training project. Analysis results will appear above the <strong>Timeline</strong> control.</p>
<p>This option is disabled when another analysis or build is in progress.</p>
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">You can also use this option to view the results of a data file (.adf) that is exported from a previous analysis (or created by using the <em>-analyze</em> option in the command-line tool).</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="odd">
<td align="left">Save</td>
<td align="left">Saves all changes to the analysis project (a.vgbproj), including clip references.</td>
</tr>
<tr class="even">
<td align="left">Remove</td>
<td align="left">Removes the analysis project from the solution.</td>
</tr>
<tr class="odd">
<td align="left">Live Preview...</td>
<td align="left">Launches VGBView with the selected gesture database.</td>
</tr>
</tbody>
</table>

<span id="ID4EAD"></span>

Analysis Project Settings  
=========================  

The analysis project settings are available in the **Properties** tab and enable you to modify analysis values, such as mirroring. The settings that are available depend on the detection technology that is used by the gesture project. For more information see [Detection Technologies](../Detection_Technologies.md).  

**Figure 2.  Analysis Project Settings**  

![](../../../../resources/k4w_vgb_analysis_project_settings.png)  
The following options are available in the **Project Settings** pane:  

| Parameter | Description                                                                                                         |
|-----------|---------------------------------------------------------------------------------------------------------------------|
| Name      | The name of the settings property. The names listed depend on the detection technology that is used by the project. |
| Value     | Assigns the value to the settings parameter.                                                                        |
| Type      | Displays the type associated with the settings property.                                                            |

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Control</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Export</td>
<td align="left"><p>Export the project property values to a file. Use this control as follows:</p>
<ul>
<li>Click the <strong>Export</strong> button. The <strong>Save As</strong> dialog window is displayed.</li>
<li>In the <strong>File name:</strong>box, enter the name of the file where you want to save the property values. If the project name is &quot;GolfSwing.a&quot;, the default file name is &quot;GolfSwing.a.fid&quot;.</li>
</ul></td>
</tr>
<tr class="even">
<td align="left">Import</td>
<td align="left"><p>Import the project property values from a file you select, such as &quot;GolfSwing.a.fid&quot;. Use this control as follows:</p>
<ul>
<li>Click the <strong>Import</strong> button. The <strong>Open</strong> dialog window is displayed.</li>
<li>In the <strong>File name:</strong> box, enter the name of the file that contains the property values to import.</li>
</ul></td>
</tr>
</tbody>
</table>

<span id="ID4EVG"></span>

Analysis Project Results  
========================  

Analysis progress will be displayed in the **Output** pane. When analysis completes, the **Project Analysis Results** will be displayed above the **Timeline** control. Multiple analysis results can be loaded for side-by-side comparison.  

If the analysis project (.a) has focus, then the collective results for all of the clips in the project will be displayed.  

**Figure 3.  Project Analysis Results**  

![](../../../../resources/k4w_vgb_analysis_project_results.png)  
The following options are available in the **Project Analysis Results** pane:  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Control</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Results</td>
<td align="left"><p>Shows the project analysis results.</p>
The results contain the number of frames compared, worst errors, average RMS, false positives, and false negatives.  
<p>Applicable results will depend on the detection technology used by the gesture project.</p></td>
</tr>
<tr class="even">
<td align="left">Clear</td>
<td align="left">Clears all the existing analysis results.</td>
</tr>
<tr class="odd">
<td align="left">Export</td>
<td align="left">Exports the selected analysis results to an .adf file, which can be loaded later for comparing results with another build.</td>
</tr>
</tbody>
</table>

To view the **Clip Analysis Results**, expand the analysis project in the **Explorer** pane and select the clip. The **Timeline** will then update to show the individual clip analysis results overlaid by the tags for easy frame-by-frame comparison.  

**Figure 4.  Clip Analysis Results**  

![](../../../../resources/k4w_vgb_analysis_project_clip.png)  
The following options are available in the **Clip Analysis Results** pane:  

| Control   | Description                                                                                                 |
|-----------|-------------------------------------------------------------------------------------------------------------|
| Show/Hide | Shows or hides the selected clip analysis results within the timeline. Tagged data will still be displayed. |

<span id="ID4E1BAC"></span>

See also  
========  

[Visual Gesture Builder user interface](../User_Interface.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Analysis Project
RLTitle : Visual Gesture Builder Analysis Project
KeywordA : O:Microsoft.Kinect.tools.k4w_analysisproject_vgb
KeywordA : 34eeda75-d178-5d34-d0eb-077dff77c174
KeywordK : Visual Gesture Builder Analysis Project
AssetID : 34eeda75-d178-5d34-d0eb-077dff77c174
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
