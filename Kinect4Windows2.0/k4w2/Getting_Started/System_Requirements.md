System Requirements  
===================  

You must meet the following system requirements to develop applications using the Kinect for Windows SDK version 2.0.  

| ![](../../resources/note.gif)Important                                                                           |
|------------------------------------------------------------------------------------------------------------------|
| Refer to the release notes for the most up-to-date info about system requirements and installation instructions. |

-   [Supported Operating Systems and Architectures](#ID4EW)  
-   [Recommended Hardware Configuration](#ID4EIB)  
-   [Software Requirements](#Software_Requirements)  
-   [Additional Software Requirements](#Add_Software_Requirements)  

<span id="ID4EW"></span>

Supported Operating Systems and Architectures  
=============================================  

The following operating systems and architectures are supported:  

-   Windows 8 (x64)  
-   Windows 8.1 (x64)  
-   Windows 8 Embedded Standard (x64)  
-   Windows 8.1 Embedded Standard (x64)  

<span id="ID4EIB"></span>

Recommended Hardware Configuration  
==================================  

Your computer must have the following minimum capabilities:  

-   64 bit (x64) processor  
-   4 GB Memory (or more)  
-   I7 3.1 GHz (or higher)  
-   Built-in USB 3.0 host controller (Intel or Renesas chipset).  

    If you're adding USB 3.0 functionality to your existing PC through an adapter, please ensure that it is a Windows 8 compliant device and that it supports Gen-2. See the troubleshooting section of [Getting Started](../Getting_Started.md) for more information.  

-   DX11 capable graphics adapter (see list of known good adapters below)  
    -   Intel HD 4400 integrated display adapter  
    -   ATI Radeon HD 5400 series  
    -   ATI Radeon HD 6570  
    -   ATI Radeon HD 7800 (256-bit GDDR5 2GB/1000Mhz)  
    -   NVidia Quadro 600  
    -   NVidia GeForce GT 640  
    -   NVidia GeForce GTX 660  
    -   NVidia Quadro K1000M  
-   A Kinect v2 sensor, which includes a power hub and USB cabling.  

| ![](../../resources/note.gif)Important                                                                                                                                                                                                                                                                                                                                                                                                     |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Many laptops switch to a low-power mode that reduces GPU performance when operating without external power. If you plan to work on a laptop that is operating on battery power, you should disable low-power mode for your GPU. In some cases, the GPU performance is limited while on battery power even when low-power mode is disabled. In this case, you should keep your laptop plugged in while using the Kinect for Windows sensor. |

| ![](../../resources/note.gif)Important                                                                                                                                                                                                                                                                                                                                                    |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| *Kinect Fusion* - When using Kinect Fusion, Kinect can process data either on a DirectX 11 compatible GPU with C++ AMP, or on the CPU, by setting the reconstruction processor type during reconstruction volume creation. The CPU processor is best suited to offline processing as only modern DirectX 11 GPUs will enable real-time and interactive frame rates during reconstruction. |

<span id="Software_Requirements"></span>

Software Requirements  
=====================  

The following developer environments are supported:  

-   All Visual Studio 2012, including Visual Studio 2012 Express ([Microsoft Visual Studio 2012 Express](http://www.microsoft.com/visualstudio/11/en-us/products/express))  
-   Visual Studio 2013 Ultimate, Premium, Professional, Community and Express for Windows Desktop  

<span id="Add_Software_Requirements"></span>

Additional Software Requirements  
================================  

The speech samples also require:  

-   [Microsoft Speech Platform Software Development Kit (Version 11)](http://www.microsoft.com/download/en/details.aspx?id=27226), if you need to compile the samples.  
-   [Microsoft Speech Platform Runtime (Version 11)](http://www.microsoft.com/download/en/details.aspx?id=27225), which is automatically installed as part of the Kinect runtime setup, if you want to run the samples only.  

The Depth-D3D and DepthWithColor-D3D samples also require:  

-   [DirectX Software Development Kit](http://www.microsoft.com/en-us/download/details.aspx?id=6812), if you need to compile the samples.  
-   [DirectX End-User Runtimes (June 2010)](http://www.microsoft.com/en-us/download/details.aspx?id=8109) if you want to run the samples only.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : System Requirements
RLTitle : System Requirements
KeywordA : O:Microsoft.Kinect.k4w_pguide_system_requirements_v2
KeywordA : 390a1540-a19d-4efa-a591-14cb33df233c
KeywordK : System Requirements
KeywordK : introduction, system requirements
AssetID : 390a1540-a19d-4efa-a591-14cb33df233c
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
