Visual Gesture Builder Interface  
================================  

This topic describes the Visual Gesture Builder (VGB) Integrated Development Environment (IDE), the Menu Bar, and the Explorer Pane.  
-   [Integrated Development Environment](#ID4EO)  
-   [Menu Bar](#ID4EZ)  
-   [Explorer Pane](#ID4EOE)  
-   [View Pane](#ID4EGF)  

<span id="ID4EO"></span>

Integrated Development Environment  
==================================  

The VGB IDE provides various window panes and menu options for producing a gesture detection database. It contains options for creating gesture projects (training and analysis), viewing and tagging .xef clips, and building/analyzing gesture detectors.  

**Figure 1.  Integrated Development Environment**  

![](../../../../resources/k4w_vgbinterface_figure1.png)  

<span id="ID4EZ"></span>

Menu Bar  
========  

The menu bar contains items that enable you to perform tasks such as opening, closing files, and viewing data.  

<span id="ID4E6"></span>
File Menu  
---------  

Click the **File** menu item to perform the tasks described next.  

![](../../../../resources/k4w_vgbinterface_filemenu.png)  

| Menu Item                      | Description                                                                                   | Short Cut        |
|--------------------------------|-----------------------------------------------------------------------------------------------|------------------|
| New Solution                   | Creates a new solution.                                                                       | **CTRL+Shift+N** |
| Open Solution                  | Opens a previously created and saved solution.                                                | **CTRL+Shift+O** |
| Add Existing Project           | Adds an existing gesture project to the solution.                                             | N/A              |
| Create New Project             | Opens the **Create Gesture Project** dialog to create a new gesture project for the solution. | N/A              |
| Create New Project with Wizard | Creates a new gesture project for the solution using the **Gesture Wizard**.                  | N/A              |
| Open Clip as Solution          | Opens a clip as a solution to inspect the tagging metadata.                                   | **CTRL+Shift+C** |
| Save                           | Saves all changes made to the solution or clip.                                               | **CTRL+S**       |
| Live Preview . . .             | Launches VGView with the selected gesture dataase.                                            | N/A              |
| Exit                           | Closes the VGB tool.                                                                          | **Alt+F4**       |

<span id="ID4EOE"></span>

Explorer Pane  
=============  

You use the Explorer Pane to navigate projects and clips. To add a project, save the solution, or build the gesture database, right-click on the solution name to open the context menu that supports those actions.  

![](../../../../resources/k4w_vgbinterface_explorerpane.png)  

You can choose different types of projects based on the detection technology. You can select [AdaBoostTrigger](../Detection_Technologies/AdaBoostTrigger.md) or [RFRProgress](../Detection_Technologies/RFRProgress.md) detection technologies.  

For each project, you can create a training version and an analysis version.  

When you create a project, the VGB tool generates XML files for each clip and adds them to the project. These XML files store tagging information associated with the clip files, which remain unmodified.  

<span id="ID4EGF"></span>

View Pane  
=========  

The view pane displays a view of the sensor data. Use the tabs, **2D** or **3D** to render either 2D or 3D data.  

<span id="ID4ERF"></span>
2D View  
-------  

![](../../../../resources/k4w_vgb_2DViewMenu.png)  

Right-click in the 2D view to get a contextual menu with the following options:  

| Menu Item            | Description                                        |
|----------------------|----------------------------------------------------|
| Depth                | Displays the depth stream in color or a grey ramp. |
| IR                   | Displays the IR stream. This is the default.       |
| Body frame           | Displays the body state, the hand state, or both.  |
| Left/Right Indicator | Displays the Left or Right indicator.              |

<span id="ID4E4G"></span>
3D View  
-------  

![](../../../../resources/k4w_vgb_3DViewMenu.png)  

Right-click in the 3D view to get a contextual menu with the following options:  

| Menu Item  | Description                                                                                                             |
|------------|-------------------------------------------------------------------------------------------------------------------------|
| Accessory  | Show/hide any or all of the view, view frustum, orientation cube, and floor plane.                                      |
| Depth      | Displays the depth stream as either a texturable surface, surface with normal, color point cloud or a grey point cloud. |
| IR         | Displays the IR stream instead of the depth stream.                                                                     |
| Body Frame | Show/hide either the body, body with joint orientation, or hand states.                                                 |



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Interface
RLTitle : Visual Gesture Builder Interface
KeywordA : O:Microsoft.Kinect.tools.k4w_menubar_vgb
KeywordA : 734b9c0b-79a6-8072-e115-60a779ee03cc
KeywordK : Visual Gesture Builder Interface
AssetID : 734b9c0b-79a6-8072-e115-60a779ee03cc
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
