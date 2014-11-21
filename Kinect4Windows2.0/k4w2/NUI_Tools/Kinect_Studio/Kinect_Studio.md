Kinect Studio Troubleshooting  
=============================  

<span id="ID4EP"></span>

Kinect Studio fails to record or playback  
=========================================  

Kinect Studio will fail to record or playback if the Kinect Studio Service (KStudioHostService.exe) or Kinect Service (KinectService.exe) is unresponsive. You may attempt to restart these services by restarting the Kinect Monitor.  

1.  Terminate Kinect Studio  
2.  Open a command prompt as Administrator.  
3.  The following commands will shut down and restart the Kinect and Kinect Studio services:  

        Net stop KinectMonitor  

        Net start KinectMonitor  

<span id="ID4EEB"></span>

Kinect Studio fails to launch  
=============================  

The Kinect Studio application state may have become corrupted. The application state such as session and custom window layout are located under:  

%LOCALAPPDATA%\\Microsoft\\KStudioWindows\\2.0  

You can clear the application state by deleting the following files under this directory.  

-   WindowsState.xml  
-   SessionState.xml  
-   Extensions.xml  

Additional application state – such as the list or most-recently used files, is located under:  

%LOCALAPPDATA%\\Microsoft\\KinectStudio\\Files  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Kinect Studio Troubleshooting
RLTitle : Kinect Studio Troubleshooting
KeywordA : O:Microsoft.Kinect.tools.k4w_natural_input_tools_KinectStudio_troubleshooting
KeywordA : 55df6330-53a3-75ad-9d47-865630bffbac
KeywordK : Kinect Studio Troubleshooting
KeywordK : Kinect Studio, output view
AssetID : 55df6330-53a3-75ad-9d47-865630bffbac
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
