Adding Kinect for Windows v2 to a Desktop or Console Application
==================================================================  

This topic provides information about adding Kinect capabilities to a desktop based application such as Windows Presentation Foundation, DirectX, and/or console applications. To work with the samples or develop your own applications, use Visual Studio 2012 or 2013, including Express and Community editions. 

### Prerequisites for Developers

Developers should be familiar with the development environment and languages to take advantage of the SDK features.

### UI Frameworks vs Console applications

The Kinect for Windows v2 SDK will provide raw camera data and does not provide capabilities to draw to a window on the desktop. If you intend to visually display the frame data, you will be required to convert that data for use with your UI framework of choice. The samples provided demonstrate this with Direct 2D and Windows Presentation Foundation. These technologies can be used as reference.

### Configuring the Development Environment

The SDK includes Kinect for Windows drivers and libraries to x64 systems only. You can still use the SDK to target either 32 or 64 bit applications, but the system must be running a 64 bit version of Windows 8/8.1. Windows N editions will need to install the media pack <http://www.microsoft.com/en-us/download/details.aspx?id=30685>. 

### Adding Kinect for Windows v2 to your Managed Application

Once you have created your application for C\# or VB.Net, perform the following steps to enable Kinect:

1.  In **Solution Explorer** tree view, right-click **References** and select **Add Reference**.  

2.  In the **Reference Manager** dialog, expand the **Assemblies** node and search for *Microsoft.Kinect*.  

3.  Then select **Microsoft.Kinect** and click **OK**.  

4.  In C\#, open MainPage.xaml.cs and add the following code to resolve the Kinect namespace:  

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
    <td align="left"><pre><code>using Microsoft.Kinect;</code></pre></td>
    </tr>
    </tbody>
    </table>

### Adding Kinect for Windows v2 to an Unmanaged C++ Application

If you have just installed the SDK, you will need to log-out or restart the system for the environment variables to become active. 

With your C++ project created and loaded in Visual Studio, follow these steps to update and include the required files:

1. From the **Project** menu, or from **Solution Explorer**, right-click on the **Project** name, and select **Properties** .

2. In the left column of the property page, click **Configuration Properties** and then **VC++ Directories** to see a list of the locations.

3. Click **Include Directories** and then click the drop-down on the far right.

4. Add **$(KINECTSDK20_DIR)\inc** and click the OK to confirm the change

5. Click **Library Directories** and then click the drop-down on the far right.

6. Add **$(KINECTSDK20_DIR)\lib\$(PlatformTarget)**. Confirm this is correct for the target type of the project and click **OK** to confirm the change

7. In the left column of the property page, expand **Linker** and click **Input**

8. Click Additional Dependencies and then click the drop-down on the far right.

9. In the list, add **kinect20.lib** and click **OK** to confirm

10. In your header file or stdafx.h file, add an entry for the following include files.
    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">stdafx.h</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><pre><code>// Windows Header Files
    #include &lt;windows.h&gt;
    #include &lt;Shlobj.h&gt;
    
    // Kinect Header file
    #include &lt;Kinect.h&gt;
    </code></pre></td>
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
