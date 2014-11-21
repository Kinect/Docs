Visual Gesture Builder solutions  
================================  

Describes the Solution menu and Global Settings tab available in Visual Gesture Builder (VGB).  
-   [Solution Menu](#ID4EN)  
-   [Global Settings Tab](#ID4E5C)  

<span id="ID4EN"></span>

Solution Menu  
=============  

To access the context menu for a solution, open the solution in VGB (**File \> New Solution or File \> Open Solution**), and right-click on the solution in the **Explorer**.  

The **Solution** menu displays options for adding new or existing gesture projects to the collection.  

**Figure 1.  Solution Menu**  

![](../../../../resources/k4w_vgb_solutions_menu.png)  
| Menu Option                    | Description                                                                                                                   |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| Add Existing Project           | Adds an existing gesture project to the solution.                                                                             |
| Create New Project             | Opens the **Create Gesture Project** dialog to create a new gesture project for the solution.                                 |
| Create New Project with Wizard | Creates a new gesture project for the solution using the **Gesture Wizard**.                                                  |
| Save                           | Saves all changes made to the solution, including changes to the global settings.                                             |
| Build                          | Builds all gesture projects in the collection. Creates a database file (.gbd) that can be used for runtime gesture detection. |
| Live Preview...                | Launches VGBView with the selected gesture database.                                                                          |

<span id="ID4E5C"></span>

Global Settings Tab  
===================  

When the solution has focus in the **Explorer**, the **Global Settings** tab will appear in the **Property** pane. Use global settings to override specific settings for all projects contained in the solution. The settings are case sensitive and must match the specific names and types used in the project. For more information on project settings, see [Detection Technologies](../Detection_Technologies.md).  

**Figure 2.  Global Settings Tab**  

![](../../../../resources/k4w_vgb_solutions_settings.png)  
| Parameter | Description                                                                                                                                                                                     |
|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Name      | Any allowed name for the settings property. The name to choose depends on the property that you want to override from the selected detection technology.                                        |
| Value     | Assign the value to the settings property.                                                                                                                                                      |
| Type      | Select the data type associated with the settings property. The type that you choose depends on the data type of the property that you want to override from the selected detection technology. |

| Button | Description                                                        |
|--------|--------------------------------------------------------------------|
| Import | Imports all global settings from an existing settings file (.fid). |
| Export | Exports all global settings to a new settings file (.fid).         |

Note that the output pane will display a message whenever a global setting is used during training:  

**Figure 3.  Output pane**  

![](../../../../resources/k4w_vgb_solutions_output.png)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Solutions
RLTitle : Visual Gesture Builder solutions
KeywordA : O:Microsoft.Kinect.tools.k4w_solution_vgb
KeywordA : 31fb326a-602e-9859-d073-334ab32fd6e7
KeywordK : Visual Gesture Builder solutions
AssetID : 31fb326a-602e-9859-d073-334ab32fd6e7
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
