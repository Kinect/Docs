VGB Command Line Options  
========================  

Use the VisualGestureBuilder command-line tool to build, analyze, and alter gesture database files.  

To use the command-line tool, run a command prompt as an administrator, and call “VisualGestureBuilder.exe \<option\>” with one of the options listed below:  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Option</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">-analyze <em>gestureAnalysisProject</em> <em>outputResultFile.adf</em></td>
<td align="left"><p>Analyzes all test clips within the <em>gestureAnalysisProject</em> (.a.vgbproj) against the specified database (.gba or .gbd) and outputs the results to <em>outputResultFile.adf</em>.</p>
<p>You can open the <em>outputResultFile.adf</em> using the <strong>Analyze</strong> button for the Analysis project from within the UI.</p></td>
</tr>
<tr class="even">
<td align="left">-build <em>buildFile</em> <em>database</em></td>
<td align="left"><p>Trains all gestures contained in the <em>buildFile</em> and saves the resulting gesture detectors to a <em>database</em>.</p>
<p>To build multiple gesture detectors, provide the solution file (.vgbsln) as the <em>buildFile</em> argument and specify a .gbd database as the result.</p>
<p>To build a single gesture detector, provide the training project (.vgbprog) as the <em>buildFile</em> argument and specify a .gba database as the result.</p></td>
</tr>
<tr class="odd">
<td align="left">-join <em>destDatabase</em> <em>srcDatabase</em> [<em>srcDatabase</em> [<em>srcDatabase</em>]...]</td>
<td align="left"><p>Joins one or more database files together. The resulting <em>destDatabase</em> file (.gbd) must be specified first. All remaining database files (.gba/.gbd) will be treated as <em>srcDatabase</em> arguments.</p>
<p>The <em>srcDestination</em> accepts the wildcard symbol (*) to support joining all/multiple databases within the same path.</p>
<p>Note: if two database files contain the same gesture name, only the first instance of that gesture will be included in <em>destDatabase</em>.</p></td>
</tr>
<tr class="even">
<td align="left">-list <em>database</em></td>
<td align="left">Opens the .gbd/.gba file specified by database and lists the gestures contained within.</td>
</tr>
<tr class="odd">
<td align="left">-split <em>database</em> <em>outputdirectory</em></td>
<td align="left">Splits the .gbd/.gba file specified by <em>database</em>, and extracts the gestures contained within. Generates the individual gestures as .gba files and saves them in the <em>outputdirectory</em> specified.</td>
</tr>
<tr class="even">
<td align="left">-rename <em>srcDatabase</em> <em>destDatabase</em> <em>oldName</em> <em>newName</em></td>
<td align="left"><p>Renames a gesture from <em>oldName</em> found in <em>srcDatabase</em> to newName. Saves the updated database as <em>destDatabase</em>.</p>
<p>Use this command to avoid naming conflicts when joining multiple gesture database files together or to allow side-by-side comparison of the same gestures across different builds.</p></td>
</tr>
<tr class="odd">
<td align="left"><em>Solution.vgbsln</em></td>
<td align="left">Launches VisualGestureBuilder and loads the specified solution file.</td>
</tr>
<tr class="even">
<td align="left"><em>Clip.vgbclip</em></td>
<td align="left">Launches VisualGestureBuilder and loads the specified clip as a solution.</td>
</tr>
<tr class="odd">
<td align="left">-?</td>
<td align="left">Displays usage information.</td>
</tr>
</tbody>
</table>

<span id="ID4EEG"></span>

Examples  
========  

Here are some examples.  

      VisualGestureBuilder -analyze c:\myDir\testProject.a.vgbproj c:\myDir\Database.gba c:\myDir\analysisResults.adf  
      VisualGestureBuilder -build c:\myDir\solution.vgbsln c:\myDir\Database.gbd  
      VisualGestureBuilder -join c:\myDir\allKickGestures.gbd c:\mySourceFilesDir\kick*  
      VisualGestureBuilder -join c:\myDir\KickAndPunchGestures.gbd c:\mySourceFilesDir\kick* c:\mySourceFilesDir\punch*  
      VisualGestureBuilder -list c:\myDir\Database.gbd  
      VisualGestureBuilder -split c:\myDir\Database.gbd c:\myGeneratedFilesDir  
      VisualGestureBuilder -rename c:\myDir\kickDatabase.gbd c:\myDir\newKickDatabase.gbd kick newKick  
      VisualGestureBuilder solutionName.vgbsln  
      VisualGestureBuilder clipFile.vgbclip  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : VGB Command Line Options
RLTitle : VGB Command Line Options
KeywordA : O:Microsoft.Kinect.tools.k4w_batchexecution_vgb
KeywordA : 9ff14824-be5d-179f-bdcc-f92688f39396
KeywordK : VGB Command Line Options
AssetID : 9ff14824-be5d-179f-bdcc-f92688f39396
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
