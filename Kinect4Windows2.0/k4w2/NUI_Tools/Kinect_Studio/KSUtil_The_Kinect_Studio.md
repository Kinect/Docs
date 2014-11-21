KSUtil - The Kinect Studio Utility Tool  
=======================================  

The Kinect Studio Utility Tool (ksutil.exe) is a simple UI tool that can be used to quickly view and compare the contents of eXtended Raw Files (XRF) and eXtended Event Files (XEF). This tool offers multiple command-line options. Uses for this tool include:  

-   Viewing stream and metadata information for raw (XRF) and processed (XEF) files  
-   Comparing stream and metadata information between two files  
-   Adding, removing, or editing metadata within a file  
-   Recording and/or playing back eXtended files (XRF or XEF)  

<span id="ID4EZ"></span>

User Interface  
==============  

![](../../../resources/k4w_ksutil_userinterface.png)  
| Button        | Description                                                               |
|---------------|---------------------------------------------------------------------------|
| View File     | Displays stream and metadata content for an eXtended (.xef or .xrf) file. |
| Compare Files | Provides side-by-side comparison of two eXtended (.xef or .xrf) files.    |
| Close File    | Closes the current view/comparison data.                                  |
| Exit          | Exits the application.                                                    |

<span id="ID4EHC"></span>

Syntax  
======  

Run the utility tool from the command line using the following syntax.  

    KSUtil.exe [options]  

<span id="ID4EQC"></span>

Command Line Options  
====================  

KSUtil.exe supports the following command line options.  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Button</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">/?</td>
<td align="left">Display usage information.</td>
</tr>
<tr class="even">
<td align="left">/view</td>
<td align="left">Display the contents of an eXtended (.xef or .xrf) file.</td>
</tr>
<tr class="odd">
<td align="left">/compare</td>
<td align="left">Compare metadata and stream content across two eXtended files.</td>
</tr>
<tr class="even">
<td align="left">/update</td>
<td align="left">Add/edit metadata in an eXtended file.</td>
</tr>
<tr class="odd">
<td align="left">/remove</td>
<td align="left">Remove metadata from an eXtended file.</td>
</tr>
<tr class="even">
<td align="left">/play</td>
<td align="left">Playback an eXtended file to the default Kinect service.</td>
</tr>
<tr class="odd">
<td align="left">/record</td>
<td align="left">Record an eXtended file for a specified duration.</td>
</tr>
<tr class="even">
<td align="left">/log</td>
<td align="left"><p>Optional command.</p>
<p>Use with /view, /compare, or /record to output the results to a .txt file.</p></td>
</tr>
<tr class="odd">
<td align="left">/loop</td>
<td align="left"><p>Optional command.</p>
<p>Use with /play to repeat playback n times before stopping.</p></td>
</tr>
<tr class="even">
<td align="left">/pii</td>
<td align="left"><p>Optional command.</p>
<p>Use with /update or /remove to modify metadata marked as ‘personally identifiable information’ in the eXtended file.</p></td>
</tr>
<tr class="odd">
<td align="left">/stream</td>
<td align="left"><p>Optional command.</p>
<p>Use with /update or /remove to alter stream-level metadata.</p>
<p>Use with –play or –record to specify which streams to play/record.</p>
<p>Supported streams include: depth, ir, body, bodyindex, color, rawir</p></td>
</tr>
</tbody>
</table>

<span id="ID4EGG"></span>

Usage Examples  
==============  

-   View \<filePath\>

        -view c:\temp\myClip.xef  

        -view c:\temp\myRawClip.xrf  

        -view c:\temp\myClip.xef –log c:\temp\myClip.txt  

-   Compare \<filePath1\> \<filePath2\>

        -compare c:\temp\myClip.xef c:\temp\myRawClip.xrf  

        -compare c:\temp\myClip.xef c:\temp\myClip2.xef –log c:\temp\myClipCompare.txt  

-   Update \<filePath\> \<metadataKey\> \<metadataValue\>

        -update c:\temp\myClip.xef newMetadataKey newMetadataValue  

        -update c:\temp\myClip.xef newKey newValue –pii  

        -update c:\temp\myClip.xef newKey newValue –stream depth ir body  

        -update c:\temp\myRawClip.xrf newKey newVlaue –pii –stream rawir  

-   Remove \<filePath\> \<metadataKey\>

        -remove c:\temp\myClip.xef metadataKey  

        -remove c:\temp\myClip.xef metadataKey –pii  

        -remove c:\temp\myClip.xef metadataKey –stream depth ir  

        -remove c:\temp\myRawClip.xrf metadataKey –pii –stream rawir  

-   Play \<filePath\>

        -play c:\temp\myClip.xef  

        -play c:\temp\myRawClip.xrf –loop 3  

        -play c:\temp\myClip.xef –stream depth ir color  

        -play c:\temp\myClip.xef –loop 2 –stream depth ir body  

-   Record \<filePath\> \<duration\>

        -record c:\temp\newClip.xef 30  

        -record c:\temp\newRawClip.xrf 10  

        -record c:\temp\newClip.xef 10 –stream depth ir body  

        -record c:\temp\newRawClip.xrf 20 –stream rawir color  

<span id="ID4EXAAC"></span>

See also  
========  

[Visual Gesture Builder user interface](../Visual_Gesture_Builder_0/User_Interface.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KSUtil - The Kinect Studio Utility Tool
RLTitle : KSUtil - The Kinect Studio Utility Tool
KeywordA : O:Microsoft.Kinect.tools.k4w_nui_tools_ksutil
KeywordA : 6d17ff0c-4a5b-df36-4d07-e75c0275e40e
KeywordK : KSUtil - The Kinect Studio Utility Tool
AssetID : 6d17ff0c-4a5b-df36-4d07-e75c0275e40e
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
