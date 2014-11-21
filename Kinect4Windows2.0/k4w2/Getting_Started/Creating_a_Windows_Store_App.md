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
