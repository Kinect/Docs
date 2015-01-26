Kinect for Windows Programming Guide  
====================================  

Welcome to version 2 of the Kinect for Windows Software Development Kit (SDK). The SDK provides the tools and APIs, both native and managed, that you need to develop Kinect-enabled applications for Microsoft Windows. Developing Kinect-enabled applications is essentially the same as developing other Windows applications, except that the Kinect SDK provides support for the features of the Kinect, including color images, depth images, audio input, and body joint data.  

Here are some examples of the types of Windows applications that you can build using the functionality supported in this SDK:  

-   Recognize and track moving people using body joint tracking.  
-   Determine the distance between an object and the sensor camera using depth data.  
-   Capture audio using noise and echo cancellation or find the location of the audio source.  
-   Enable voice-activated applications by programming a grammar for use with a speech recognition engine.
-   Enable custom application features through recognition of body gestures.
-   Determine facial features such as skin color, and hair color.
-   Recognize facial movement such as smiling, mouth open, eye closure, lip, jaw and eyebrow movement  

<span id="ID4EAB"></span>

Contents of the Kinect for Windows SDK  
======================================  

The SDK includes:  

-   Drivers and technical documentation for implementing Kinect-enabled applications using a Kinect for Windows sensor.  
-   Reference APIs and documentation for programming in [managed](Reference/Kinect_for_Windows_v2.md) and [unmanaged](Reference/C++_Reference.md) code. The APIs deliver multiple media streams with minimal software latency across various video, CPU, and device variables.
-   [NUI tools](../NUI_Tools.md) for creating custom gestures, testing, recording and playback.  
-   Samples that demonstrate good practices for using a Kinect sensor.  
-   Example code that breaks down the samples into user tasks.  

<span id="ID4EZB"></span>

In this section  
===============  

[Lean tracking](Programming_Guide/Lean_tracking.md)    
Demonstrates how to use the lean tracking APIs.  

[Body tracking](Programming_Guide/Body_tracking.md)    
Discusses how to use Kinect body tracking.  

[Face tracking](Programming_Guide/Face_tracking.md)    
This topic provides an overview of the programming model for Kinect face tracking.  

[High definition face tracking](Programming_Guide/High_definition_face.md)    
Discusses the PayForPlay high definition face tracking API.  

[Coordinate mapping](Programming_Guide/Coordinate_mapping.md)    
This topic explains how to use coordinate mapping to project Kinect data between coordinate spaces.  

[Kinect API Overview](Programming_Guide/Kinect_API_Overview.md)    
Provides an overview of the APIs available for Kinect for Windows apps.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Programming Guide
RLTitle : Kinect for Windows Programming Guide
KeywordA : O:Microsoft.Kinect.k4w_pguide_v2
KeywordA : 7df5af6d-e4fe-e19d-2512-6b20711147d2
KeywordK : Kinect for Windows Programming Guide
AssetID : 7df5af6d-e4fe-e19d-2512-6b20711147d2
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
