KSCONVERT - The Kinect Studio Clip Conversion Tool  
==================================================  

The Kinect Studio Clip Conversion tool (ksconvert.exe) is a command-line tool that is used to convert eXtended Raw Files (XRF) and eXtended Event Files (XEF). Uses of this tool include:  

-   Converting raw data (XRF) into processed data (XEF)  
-   Upgrading data from an older format to the current format  
-   Transforming, decoding, or archiving/unarchiving data.  

Clips that contain raw data captured directly from the sensor array are not directly usable by applications, whereas clips that contain processed data are usable by applications.  

-   [Syntax](#ID4E5)  
-   [Command Line Options](#ID4EHB)  
-   [Usage Examples](#ID4EEE)  
-   [Best Practices](#ID4EIF)  

<span id="ID4E5"></span>

Syntax  
======  

Run the conversion tool from the command line using the following syntax.  

    KSConvert.exe [options] source destination  

<span id="ID4EHB"></span>

Command Line Options  
====================  

KSConvert.exe supports the following command-line options.  

| Option       | Description                                                                                                                                                                                              |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| /?           | Displays usage information.                                                                                                                                                                              |
| /nologo      | Suppresses copyright messages.                                                                                                                                                                           |
| /c           | Continues conversion in a batch even if an error is encountered while converting a file.                                                                                                                 |
| /s           | Searches the specified directory and all subdirectories for source files for conversion.                                                                                                                 |
| /archive     | Prepares clips for archival purposes by compressing the data at the individual stream-level. Some compression techniques are domain specific to maximize compression, thus yielding a much smaller file. |
| /unarchive   | Removes data compression of streams within a file, which will return the file to a playable state.                                                                                                       |
| /DecodeColor | Decodes a compressed color stream into an uncompressed color stream.                                                                                                                                     |
| /StripColor  | Does not copy the color stream to the result file. Removing color can significantly decrease the size of the result file.                                                                                |
| /pii         | Copies metadata marked as ‘personally identifiable information’ to the result file. All other metadata will be copied by default.                                                                        |
| source       | Specifies a file to convert, either a raw capture (XRF) or a previously processed clip (XEF). This file may be located on the computer.                                                                  |
| destination  | Specifies a name for the converted file.                                                                                                                                                                 |

<span id="ID4EEE"></span>

Usage Examples  
==============  

-   Convert a raw XRF into a processed XEF:  

        ksconvert raw.xrf processed.xef  

-   Convert an older, existing XEF into an upgraded, processed XEF:  

        ksconvert existing.xef processed.xef  

-   Compress a raw XRF on the computer and write the result file to a network share:  

        ksconvert /compress d:\clips\rawIR.xrf \\myshare\compressedIR.xrf  

-   Unarchive a raw XRF on a network share and strip color from the result file:  

        ksconvert /unarchive /StripColor \\myshare\compressedIRColor.xrf \\myshare\RawIRNoColor.xrf  

<span id="ID4EIF"></span>

Best Practices  
==============  

KSConvert.exe can perform the following operations:  

-   Converting raw data (IR) into processed data (depth, IR, body).  
-   Updating raw data (depth, IR, and body if the user was tracked) or a processed file (body if the user was tracked) to the latest data format.  

The KSConvert.exe tool is updated periodically to work with the latest version of Kinect runtime. Use the tool to convert input data (either raw or processed) to data that matches the latest version of the Kinect runtime. This allows you to preserve your investment in capture clips. Perform the following steps:  

1.  Record sensor data. E.g. Capture gestures and save them in a XRF/XEF file.  
2.  Upgrade your computer to the latest SDK.  
3.  Run KSConvert.exe on your existing XRF/XEF file. Any new SDK improvements are also added to the XEF file.  
4.  Use the updated XEF file with the rest of the SDK tools.  

Processed data files are significantly smaller than raw data files, but they are limited in the amount of Kinect data that can be regenerated. Be sure to save your raw data as you can use this tool to update them to the latest data format.  

If long-term storage capacity is limited, be sure to archive the raw files before committing them to storage.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KSCONVERT - The Kinect Studio Clip Conversion Tool
RLTitle : KSCONVERT - The Kinect Studio Clip Conversion Tool
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_KinectStudio_ksconvert
KeywordA : e32917bd-479c-3eef-9b72-068b91dd1690
KeywordK : KSCONVERT - The Kinect Studio Clip Conversion Tool
KeywordK : Kinect Studio, ksconvert
AssetID : e32917bd-479c-3eef-9b72-068b91dd1690
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
