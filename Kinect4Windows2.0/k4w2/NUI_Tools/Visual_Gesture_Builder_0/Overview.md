Visual Gesture Builder: Overview  
================================  

Visual Gesture Builder (VGB) generates data that applications use to perform gesture detection at run time. Even for simple cases, gesture detection is a challenging task that may require many lines of code to obtain reliable results, considering all of the different users and spaces that an application might encounter. By using a data-driven model, VGB shifts the emphasis from writing code to building gesture detection that is testable, repeatable, configurable, and database-driven. This method provides better gesture recognition and reduces development time.  

VGB uses a number of detection technologies. The user selects the detection technologies to use—namely [AdaBoostTrigger](Detection_Technologies/AdaBoostTrigger.md) or [RFRProgress](Detection_Technologies/RFRProgress.md)—and tags frames in a clip related to a meaningful gesture, such as a punch or a kick. At the end of the tagging process, VGB builds a gesture database; with this database, an application can process body input from a user to, for example, detect a hit or swing progress.  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><img src="../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Because of potential changes in the NUI processing pipeline, the VGB tagging/training process, we recommended that you rebuild the VGB gesture database (a .gbd file) that is used by the VGB runtime and <a href="User_Interface/Live_Preview.md">Live Preview</a> whenever a new version of the SDK is adopted or installed. Rebuilding the VGB database does not require any changes to the metadata or to the tagging data. Because of potential changes in the Kinect processing pipeline, the VGB tagging/training process, or the pay-to-play technologies, we recommended that you perform the following steps whenever a new version of the SDK is adopted or installed:  
<ol>
<li>Use <a href="../Kinect_Studio/KSCONVERT_The_Kinect_Studio.md">KSCONVERT - The Kinect Studio Clip Conversion Tool</a> to update clips to the latest body stream.</li>
<li>Rebuild the VGB gesture database (.gbd file) that is used by the VGB runtime and <a href="User_Interface/Live_Preview.md">Live Preview</a>. Rebuilding the VGB database does not require any changes to the metadata or to the tagging data.</li>
</ol></td>
</tr>
</tbody>
</table>

The following are some of the results of using VGB:  

-   Mitigating the current code-intensive approach.  
-   Reusing gesture definitions in different versions of the same application.  
-   Sharing gesture definitions among applications.  
-   Creating a library of gesture definitions.  
-   Improving the predictability and reliability of gesture definitions.  
-   Testing framework for gesture detection.  
-   Analyzing and visualizing gesture-detection results.  
-   Managing a large quantity of data in a user friendly IDE.  

<span id="ID4EEC"></span>

Using Visual Gesture Builder  
============================  

The following are the basic steps for using Visual Gesture Builder:  

1.  Create a *solution*.  

    A solution contains a group of gesture projects.  

2.  Create one or more *projects*.  

    A gesture project has a gesture tag and a detection technology associated with it.  

3.  Add a set of clip files to each project.  

    A clip is a file with example data that machine learning algorithms can train on.  

4.  Tag the frames in the clip files associated with each gesture.  
5.  Build a training gesture database.  

The following illustration shows the context in which Visual Gesture Builder is used.  

**Figure 1.  Visual Gesture Builder in Context**  

![Visual Gesture Builder in Context](../../../resources/k4w_VisualGestureBuilder_Context.png)  

<span id="ID4EVD"></span>

Brief survey of additional features  
===================================  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Feature</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">AdaBoostTrigger</td>
<td align="left">The <a href="Detection_Technologies/AdaBoostTrigger.md">AdaBoostTrigger</a> is a binary technology type. It uses an Adaptive Boosting (AdaBoost) machine learning algorithm to determine when a user performs a certain gesture.</td>
</tr>
<tr class="even">
<td align="left">Command Line</td>
<td align="left">Allows running Visual Gesture Builder from the command line. This is useful when building or analyzing multiple gesture databases using a batch file. For more information, see <a href="VGB_Command_Line_Options.md">VGB Command Line Options</a>.</td>
</tr>
<tr class="odd">
<td align="left">Live Preview</td>
<td align="left">Enables a developer to quickly view the results of a gesture database on the computer in real-time, without having to integrate the database into an application.</td>
</tr>
<tr class="even">
<td align="left">RFRProgress</td>
<td align="left">The <a href="Detection_Technologies/RFRProgress.md">RFRProgress</a> is a detection technology that produces an analog or continuous result. It uses the Random Forest Regression (RFR) machine learning algorithm to determine the progress of a gesture performed by a user.</td>
</tr>
<tr class="odd">
<td align="left">Training Optimization</td>
<td align="left"><ul>
<li>Allows excluding frames from training clips, which can reduce training times and reduce memory usage.</li>
<li>Allows reusing data that has not changed.</li>
<li>With training optimization, <a href="Detection_Technologies/AdaBoostTrigger.md">AdaBoostTrigger</a> is up to two times faster on the computer, while producing the same recognition results.</li>
</ul></td>
</tr>
<tr class="even">
<td align="left">Viewing 2D</td>
<td align="left">Allows rendering of 2D depth, infrared, and body streams.</td>
</tr>
<tr class="odd">
<td align="left">Viewing 3D</td>
<td align="left">Allows rendering of 3D accessory and depth, infrared, and body streams.</td>
</tr>
</tbody>
</table>



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Overview
RLTitle : Visual Gesture Builder: Overview
KeywordA : O:Microsoft.Kinect.tools.k4w_overview_vgb
KeywordA : 2aa9c109-3807-f72c-407c-9b1139411f8e
KeywordK : Visual Gesture Builder: Overview
AssetID : 2aa9c109-3807-f72c-407c-9b1139411f8e
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
