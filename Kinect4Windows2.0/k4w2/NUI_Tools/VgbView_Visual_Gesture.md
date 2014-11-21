VgbView - Visual Gesture Builder View  
=====================================  

VgbView is a tool that allows you to view a gesture database in real time, without first integrating the database into an application.  

Use VgbView to quickly iterate and experiment with various project settings, comparing the results in terms of accuracy, run time memory, and CPU requirements.  

Designers and technical artists can use VgbView to view the gesture database before database access is added to application code.  

| ![](../../resources/note.gif)Note                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Because of the potential changes in the areas such as the NUI processing pipeline, the Visual Gesture Builder (VGB) tagging/training process and pay-to-play technologies, you need to use the latest SDK to rebuild the VGB gesture database to be consumable by VgbView. However, no changes to the metadata or tagging data are required to rebuild a VGB database. To rebuild a VGB database, load a VGB project (.vgbproj) from Visual Gesture Builder and then select **Build** to build a database. |

<span id="ID4EX"></span>

Launching VgbView  
=================  

To launch VgbView in Visual Gesture Builder:  

-   On the **File** menu of Visual Gesture Builder, click **Live Preview**.  
-   In the **Open** dialog, navigate to the desired gesture database and then click **Open**.  

A script will run and display information in the Output window on the development computer, and then activate VgbView on the computer.  

**Figure 1.  The VgbView user interface**  

![](../../resources/k4w_VgbView_interface.png)  

<span id="ID4EUB"></span>

Control Actions  
===============  

The following control functionality is currently available in VgbView.  

1.  Use the **O** key to load alternate database files. This can be useful to quickly compare database files. For example, to compare the same gestures built with various project settings.  
2.  Use the **M** key to toggle between polling and event notification. When polling, the VGB CPU rate will be visible. When using event notification, the VGB frame rate will be visible.  

<span id="ID4EIC"></span>

Essential Information  
=====================  

VgbView currently displays the following information.  

-   The gesture database file that is currently loaded.  
-   The name of each gesture.  
-   The detection graph for each gesture.  

<span id="ID4EYC"></span>

See also  
========  

[Visual Gesture Builder user interface](Visual_Gesture_Builder_0/User_Interface.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : VgbView - Visual Gesture Builder View
RLTitle : VgbView - Visual Gesture Builder View
KeywordA : O:Microsoft.Kinect.tools.k4w_nui_tools_vgbview
KeywordA : 7a19f42e-33b8-27a5-3b1d-ac08085e09c5
KeywordK : VgbView - Visual Gesture Builder View
AssetID : 7a19f42e-33b8-27a5-3b1d-ac08085e09c5
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
