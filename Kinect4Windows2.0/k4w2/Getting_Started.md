Getting Started  
===============  

This topic contains additional resources that will help you to develop a Kinect-enabled application. This includes the release notes for the SDK, instructions for getting started creating projects using Visual Studio, and lots of links to blogs, published papers, and other SDKs that you may need.  

-   [License Agreement](#License_Agreement)  
-   [System Requirements](#System_Requirements)  
-   [Installation](#Installation)  
-   [Getting Help](#Getting_Help)  

<span id="License_Agreement"></span>

License Agreement  
=================  

By downloading, installing, accessing, or using the Microsoft Kinect for Windows Software Development Kit 2.0 (SDK), you agree to be bound by the terms of its license. Please read the Microsoft Kinect for Windows SDK license provided as part of this software.  

<span id="System_Requirements"></span>

System Requirements  
===================  

See [System Requirements](Getting_Started/System_Requirements.md).  

<span id="Installation"></span>

Installation  
============  

<span id="Install"></span>
Installation  
------------  

1.  Download and launch the KinectSDK-v2.0\_1409-Setup executable from <http://go.microsoft.com/fwlink/?LinkID=403899> and wait for setup to complete before moving on to step 2.  
2.  Ensure that the Kinect sensor is connected to the power hub and the power hub is plugged into an outlet. Plug the USB cable from the power hub into a USB 3.0 port on your computer. Driver installation will begin automatically.  

3.  Wait for driver installation to complete. You can verify that installation has completed by launching Device Manager and verifying that "KinectSensor Device" exists in the device list.  

    | ![](../resources/note.gif)Note                                                                                                                  |
    |-------------------------------------------------------------------------------------------------------------------------------------------------|
    | On first plugin, the firmware on the device will be updated. This may result in device enumeration happening several times in the first minute. |

4.  Installation is now complete.  

<span id="ID4ERC"></span>
Verify that the driver is installed correctly  
---------------------------------------------  

To verify that the Kinect driver has been correctly installed, perform the following steps:  

1.  Ensure that **Kinect Monitor Service** is started and running from the **Services** control panel.  
2.  The three red LEDs on the Kinect sensor should be lit.  
3.  The Kinect sensor should appear in **Device Manager** as the following nodes under **Audio inputs and outputs**: **Microphone Array (Xbox NUI Sensor)**, **KinectSensor Device**: **WDF Petra KinectSensor Interface 0**, and **Sound, video and game controllers**: **Xbox NUI Sensor**.  
4.  The Kinect sensor's microphone array will appear under **Sound, video and game controllers** in **Device Manager** as: **Kinect for Windows USB Audio**.  

<span id="ID4E2D"></span>
Troubleshooting  
---------------  

As the first step in trouble shooting, we recommend running the Kinect Configuration Verifier tool. This tool is available in the SDK Browser, and will determine if your hardware is a supported configuration.  

-   Samples don’t show any output from the sensor.  
    -   Verify that the Kinect Sensor, power hub, and USB 3.0 cables are all connected properly.  
    -   Verify that only a single instance of **KinectMonitor.exe** is running (through TaskManager)  
    -   In some instances, you may need to completely power cycle the power hub by unplugging it from the power outlet.  
    -   If you have additional USB devices attached to the computer, remove them and try again with only the Kinect Sensor attached. Also, see the USB 3.0 section below.  
    -   Ensure that your system meets the recommended hardware configuration outlined above.  
    -   Reboot  
-   The Infrared stream is returning all zeroes. (In this case, InfraredBasics will show a black screen, while color and depth basics will be streaming correctly.)  
    -   You are likely on an NVidia GPU with an old driver. Ensure that you have the latest WHQL driver installed from [NVidia’s website](http://www.nvidia.com/download/driverResults.aspx/75992/en-us).  
-   The Speech samples crash.  
    -   Ensure that you have the x86 version of the Speech runtime installed.  
-   USB 3.0  
    -   If you’re adding USB 3.0 functionality to a current system by installing a USB 3.0 host adapter (PCIe), verify that the USB 3.0 host adapter supports Gen-2. Note that you may have to try different PCI-e slots to find one that provides the USB bandwidth required by the sensor. We’ve found that plugging the host adapter into one of the graphics slots works best.  
    -   If you receive a notification from the OS that there are not enough resources for this device, it means there are other devices which are reserving bandwidth on your controller, and the Kinect cannot currently function. First, try removing high bandwidth devices, such as a webcam, from that controller. If this does not resolve the problem, try to reboot. For integrated controllers, this will often solve the issue. If the problem persists, you may have to add a discrete USB3 controller to your system, or explicitly disable whatever device is causing the conflict.  

<span id="Getting_Help"></span>

Getting Help  
============  

Online developer resources for Kinect for Windows include the following:  

-   [Technical Resources on the Kinect for Windows Website](http://www.microsoft.com/en-us/kinectforwindows/develop/resources.aspx)  
-   [The Kinect for Windows v2 Human Interface Guidelines (HIG)](http://download.microsoft.com/download/6/7/6/676611B4-1982-47A4-A42E-4CF84E1095A8/KinectHIG.2.0.pdf)  
-   [The Kinect for Windows Blog](http://blogs.msdn.com/b/kinectforwindows/)  
-   [Kinect for Windows v2 SDK Forums](http://social.msdn.microsoft.com/Forums/en-US/home?forum=kinectv2sdk)  
-   [Coding4Fun Kinect Showcase](http://channel9.msdn.com/coding4fun/kinect)  

For general Windows development questions, try the following:  

-   [Microsoft Developer Network](http://msdn.microsoft.com) (http://msdn.microsoft.com): The latest development documentation to help you create applications for Windows.  
-   [Microsoft TechNet](http://technet.microsoft.com) (http://technet.microsoft.com): The latest administration documentation to help you administer the Windows operating system.  

<span id="ID4ESH"></span>

In this section  
===============  

[System Requirements](Getting_Started/System_Requirements.md)    
System requirements for Kinect for Windows SDK 2.0  

[Creating a Windows Store App that Uses Kinect for Windows SDK](Getting_Started/Creating_a_Windows_Store_App.md)    
Provides step-by-step information about creating a Windows Store app project that uses the Kinect sensor.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Getting Started
RLTitle : Getting Started
KeywordA : O:Microsoft.Kinect.k4w_pguide_resources_v2
KeywordA : 40c0aa6f-5094-2891-fb5b-be2893a4e4bf
KeywordK : Getting Started
KeywordK : Resource, Overview
KeywordK : troubleshooting, Kinect for Windows SDK
KeywordK : installation
AssetID : 40c0aa6f-5094-2891-fb5b-be2893a4e4bf
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
