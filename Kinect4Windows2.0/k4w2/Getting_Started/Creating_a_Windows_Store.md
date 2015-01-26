Creating a Windows Store App that Uses Kinect for Windows SDK  
=============================================================  

This topic provides step-by-step information about creating a Kinect enabled Windows Store app.  

### Enabling the Kinect sensor in your Windows Store app project  

To add Kinect capabilities to your C\# or C++ project, perform the following steps:  

1.  Create a new C\#/C++ Windows Store app, or open an existing project  
2.  In **Solution Explorer** tree view, right-click **References** and select **Add Reference**.  

3.  In the **Reference Manager** dialog:  

    -   In Windows 8.0, expand the **Windows** node and select **Extensions**.  
    -   In Windows 8.1, expand the **Windows 8.1** node and select **Extensions**.  

4.  Then select **WindowsPreview.Kinect** and click **OK**.  
5.  Open your project's **Package.appxmanifest** and click on the **Capabilites** tab.  

6.  Check the **Microphone** and **Webcam** check boxes.  

    ![](../../resources/k4w_sensor_capabilites.png)  

7.  If your project is in C\#, open MainPage.xaml.cs and add the following code:  

    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">C#</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><pre><code>using WindowsPreview.Kinect;</code></pre></td>
    </tr>
    </tbody>
    </table>

    If your project is in C++, open MainPage.xaml.cpp and add the following code:  

    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">C++</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><pre><code>using namespace WindowsPreview::Kinect;</code></pre></td>
    </tr>
    </tbody>
    </table>

    Alternatively, you can add the following code instead of the above:  

    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">C++</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><pre><code>namespace Kinect = WindowsPreview::Kinect;</code></pre></td>
    </tr>
    </tbody>
    </table>

#### Unity Pro Windows Store development
To publish a Unity based application to the Windows Studio you will need to have Visual Studio 2013 on your machine. Unity will be able to generate a Visual Studio project that can be opened in the Visual Studio IDE to complete the publishing process. When you are ready to test your Unity application with Windows Store, follow these steps:

1. From the **Unity** editor window, as of version 4.6.1f1, open the File menu and select **Build Settings... Ctrl-Shift-B**
2. Select **Windows Store** from the **Platform** list at the bottom left
3. Ensure the **SDK** setting is either **8.1** or **Universal 8.1**
4. Click the **Player Settings...** button. In the editor's **Inspector** panel, expand **Publishing Settings** and update **Capabilities** to include **WebCam *and* Microphone**. These settings can also be updated in Visual Studio later on
5. Go back to the **Build Settings** window and click the **Build** button
6. Choose a location to save the project and note this location

To complete the process of creating the Windows Store application you will need to run the **Visual Studio 2013 IDE**. If you are using an **Express** edition, be sure to use the **Windows Store** version. From the Visual Studio:

1. Open the solution(.sln) file that was generated in the folder generated from step 6 above
2. From the **Solution** tree view, expand the *project name* is expanded to reveal the **References**
3. Right-click **References** and select **Add Reference**
4. In the Reference Manager dialog, expand the **Windows 8.1** node and select **Extensions**
5. Then select **WindowsPreview.Kinect** and click **OK**
6. You can now build and test the application and follow the Windows Store publishing guidelines as you would any Windows Store application


<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Creating a Windows Store App that Uses Kinect for Windows SDK
RLTitle : Creating a Windows Store App that Uses Kinect for Windows SDK
KeywordA : O:Microsoft.Kinect.creating_win_store_app_v2
KeywordA : 91b4555d-14d9-8586-8641-a69bdf48239e
KeywordK : Creating a Windows Store App that Uses Kinect for Windows SDK
KeywordK : creating a project
KeywordK : Windows Store App
AssetID : 91b4555d-14d9-8586-8641-a69bdf48239e
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
