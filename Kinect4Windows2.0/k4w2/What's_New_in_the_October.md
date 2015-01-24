What's New in the October 2014 Kinect for Windows version 2.0 SDK  
=================================================================  

The October 2014 release of the Kinect for Windows 2.0 SDK from Microsoft contains the following new features, tools, and documentation:  

<span id="ID4ER"></span>

Changes for this release  
========================  

**Windows Store Support**    
With this release of Kinect for Windows, you are able to develop and publish Kinect enabled applications which target the Windows Store. We are incredibly excited to see what people create. All of the Kinect SDK and sensor functionality are available in this API surface, except for Speech. For more information about developing Windows Store applications which use Kinect, please see: <http://www.microsoft.com/en-us/kinectforwindows/business/windowsstore-apps.aspx#tab=2>.  

**Unity Support**    
For the first time, the Kinect API set is available in Unity Pro, through a Unity Package. We are excited to be able to offer the platform to our developers. APIs for Kinect for Windows core functionality, visual gesture builder and face are now available to be called from Unity apps. The Unity plugins are available for download at: <http://go.microsoft.com/fwlink/?LinkID=513177>

**.NET APIs**    
The Managed API set should feel familiar to developers who worked with our managed APIs in the past. We know this is one of the fastest development environments available, and that many development shops have an existing investment in this space. All of the Kinect SDK and sensor functionality are available in this API surface.  

**Native APIs**    
Many Kinect applications require the full power and speed that writing native C++ code requires. We are excited to share this iteration of the native APIs for Kinect. The form and structure of the APIs is identical to the Managed API set, but allow a developer to access the full speed of C++. These APIs are a significant divergence from the v1.x native APIs, and should be significantly easier to use. All of the Kinect SDK and sensor functionality are available in this API surface.  

**Audio**    
The Kinect sensor and SDK provide a best in class array microphone and advanced signal processing to create a virtual, software based microphone which is highly directional, and which can understand the direction sounds are coming from. In addition, this provides a very high quality input for Speech recognition.  

**Face APIs**    
Extended massively from v1, the Face APIs provide a wide variety of functionality to enable rich face experiences and scenarios. Within the Face APIs, developers will be able to detect faces in view of the sensor, align them to 5 unique facial identifiers, and track orientation in real-time. With HD Face, the technology provides 94 unique "shape units" per face, to create meshes with a very rich likeness to the user. The meshes can be tracked in real-time to show rich expressiveness and live tracking of the user's facial movements and expressions.  

**Kinect for Windows v2 Hand Pointer Gestures Support**    
If you would like to enable your applications to be controls through hand pointer gestures, Kinect for Windows v2 has improved support. See ControlsBasics-XAML, ControlsBasics-WPF and ControlsBasics-DX for examples of how to hand pointer gesture enable your applications. This is an evolution of the KinectRegion/KinectUserViewer support that we provided in Kinect for Windows v1.7 and later. KinectRegion and KinectUserViewer are available for XAML and WPF applications. The DirectX support is built on top of a lower level Toolkit Input component.  

**Kinect Fusion**    
With this release of Kinect for Windows, you are able develop and deploy Kinect Fusion applications. This provides higher resolution, better camera tracking and performance than the 1.x releases of Kinect Fusion.  

**Kinect Studio**    
Kinect Studio has had a major rewrite since the v1 days, in order to handle the new sensor, and to provide users with more customization and control. The new user-interface offers flexibility in the layout of various workspaces and customization of the different views. It is now possible e.g. to compare two 2D or 3D views side-by-side or to create a custom layout to meet your needs. The separation of the monitoring, recording and playback streams exposes additional functionality such as file- and stream-level metadata. The timeline features: in- and out-points to control what portion of the playback to play; pause-points that let you set multiple points at which to suspend a playback; markers, that let you attach meta-data to various points in time. This preview also exposes playback looping and additional 2D/3D visualization settings. There is still some 'placeholder' artwork here and there, but the tooltips should guide you along.  

**Visual Gesture Builder (Preview)**    
Introducing Visual Gesture Builder, a gesture detector builder that uses machine-learning and body-frame data to 'define' a gesture. Multiple body-data clips are marked (aka 'tagged') with metadata about the gesture which is then used by a machine-learning trainer during the build step to extract a gesture definition from the body-data clips. The gesture definition can subsequently be used by the gesture detection runtime - called by your application - to detect one or more gestures. While using machine-learning for gesture detection is not for the faint of heart, it offers a path to rapid prototyping. Using vgbview, you can benchmark your gesture definitions without requiring that you write any code. For detailed walkthrough videos and a whitepaper on using VGB, please see the resources at: <https://social.msdn.microsoft.com/Forums/en-US/02e0302a-e3bd-46d3-9146-0dacd11d2a8d/deep-dive-videos-and-whitepaper-for-visual-gesture-builder?forum=kinectv2sdk>.  

**Samples**    
There is an extensive set of samples available through the SDKBrowser, across a range of languages and frameworks:  

-   Audio Basics-(D2D, WPF)  
-   Audio Basics (IStream) -D2D  
-   Audio Capture-Console (Raw)  
-   Body Basics-(D2D, HTML, WPF, XAML)  
-   Color Basics-(D2D, HTML, WPF, XAML)  
-   Controls Basics-(DX, WPF, XAML)  
-   Coordinate Mapping Basics (D2D, HTML, WPF, XAML)  
-   Depth Basics (D2D, HTML, WPF, XAML)  
-   Discrete Gesture Basics (WPF)  
-   Face Basics (D2D, HTML, WPF)  
-   HD Face Basics (WPF, XAML, XAML-CPP)  
-   Infrared Basics (D2D, HTML, WPF, XAML)  
-   Kinect Fusion Basics (D2D)  
-   Kinect Fusion Explorer (D2D, WPF)  
-   Speech Basics (D2D, WPF)  

    | ![](../resources/note.gif)Note                                                                                                                  |
    |-------------------------------------------------------------------------------------------------------------------------------------------------|
    | In order to run the speech samples, you need to install the Speech Runtime. In order to build the speech samples, you need to install the Speech SDK.  You can find download links to the Speech SDK under "Additional Software Requirements" at [System Requirements](Getting_Started/System_Requirements.md)  |


<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : What's New in the October 2014 Kinect for Windows version 2.0 SDK
RLTitle : What's New in the October 2014 Kinect for Windows version 2.0 SDK
KeywordA : O:Microsoft.Kinect.k4w_whats_new_v2
KeywordA : 0d75be2c-ffe8-64a3-3889-bae4db0554de
KeywordK : What's New in the October 2014 Kinect for Windows version 2.0 SDK
KeywordK : introduction, system requirements
AssetID : 0d75be2c-ffe8-64a3-3889-bae4db0554de
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
