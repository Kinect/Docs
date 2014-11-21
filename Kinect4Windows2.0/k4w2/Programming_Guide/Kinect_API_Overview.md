Kinect API Overview  
===================  

This topic provides a high-level overview of the APIs that you can use to develop Kinect for Windows applications.  

The Kinect for Windows SDK 2.0 provides three different API sets that can be used to create Kinect-enabled applications. A set of Windows Runtime APIs is provided to support the development of Windows Store applications. A set of .NET APIs is provided to support the development of WPF applications. And a set of native APIs is provided to support applications that require the performance advantages of native code.  

For clarity and readability, the APIs linked to in this topic are all from the Windows Runtime API set. But the APIs and programming concepts discussed apply to all three API sets. For detailed API reference documentation, see [Reference](../Reference.md).  

-   [Video data](#ID4E3)  
-   [Audio data](#ID4EELAC)  

<span id="ID4E3"></span>

Video data  
==========  

Video data from the Kinect sensor includes low-level data, such as infrared and color, as well as processed data, like depth and body (commonly referred to as *skeleton*). These APIs have been designed to follow standard WinRT design guidelines, which support all WinRT-compatible languages and UI frameworks.  

<span id="ID4EIB"></span>
Sensor Acquisition and Startup  
------------------------------  

Kinect for Windows supports one sensor, which is called the *default sensor*. The [KinectSensor Class](../Reference/Kinect_for_Windows_v2/Kinect/KinectSensor_Class.md) has static members to help configure the Kinect sensor and access sensor data.  

The key APIs are:  

-   [KinectSensor.GetDefault Method](../Reference/Kinect_for_Windows_v2/Kinect/KinectSensor_Class/Methods/GetDefault_Method.md)  
-   [KinectSensor.Open Method](../Reference/Kinect_for_Windows_v2/Kinect/KinectSensor_Class/Methods/Open_Method.md)  

The [KinectSensor.IsOpen Property](../Reference/Kinect_for_Windows_v2/Kinect/KinectSensor_Class/Properties/IsOpen_Property.md) will return true if the calling process has called [Open](../Reference/Kinect_for_Windows_v2/Kinect/KinectSensor_Class/Methods/Open_Method.md).  

The [KinectSensor.IsAvailable Property](../Reference/Kinect_for_Windows_v2/Kinect/KinectSensor_Class/Properties/IsAvailable_Property.md) will return false if no Kinect sensor is available. For example, false is returned if a user installed your application, but does not have a Kinect sensor connected to their PC. If this is the case, your application should display a message to the user indicating that the sensor is unavailable.  

<span id="ID4EXC"></span>
Data sources  
------------  

Use the sensor to access data from several sources including: color, depth, body, body index, and infrared. Functionally, each source is controlled by the following three things:  

**Source type**    
Inspect or configure a source and open a source reader.  

**Source reader type**    
Access to the source's frames using eventing or polling.  

**Frame type**    
Access the data from a particular frame from the source.  

For examples of how these are represented in the API, see the following topics:  

-   [FrameSourceTypes Enumeration](../Reference/Kinect_for_Windows_v2/Kinect/FrameSourceTypes_Enumeration.md)  
-   [FrameDescription Class](../Reference/Kinect_for_Windows_v2/Kinect/FrameDescription_Class.md)  
-   [ColorImageFormat Enumeration](../Reference/Kinect_for_Windows_v2/Kinect/ColorImageFormat_Enumeration.md)  
-   [ColorFrameSource.OpenReader Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrameSource_Class/Methods/OpenReader_Method.md)  

<span id="ID4EQE"></span>
Streams  
-------  

Once a developer has an open sensor, they can use that instance to gain access to the individual streams: color, depth, body, body index, infrared, and long exposure infrared. Each stream is broken up into 3 basic pieces:  

**Stream type**    
Lets you inspect or set the stream settings and allows you to open a stream reader.  

**Stream reader type**    
Gives you access to the stream's frames via eventing or polling.  

**Frame type**    
Gives you access to the data from a particular frame off of the stream.  

The stream type's job is to give you access to the stream and allow you to configure it (if in exclusive mode) and open a stream reader. Each stream has its own type, but they all share the same basic functionality.  

| API element                                                                                                                                                    | Description                                                                                                                                                                         |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [BodyIndexFrameSource.OpenReader Method](../Reference/Kinect_for_Windows_v2/Kinect/BodyIndexFrameSource_Class/Methods/OpenReader_Method.md)                    | Opens a reader for this stream. This will fail if conflicting streams are already open.                                                                                             |
| [BodyIndexFrameSource.IsActive Property](../Reference/Kinect_for_Windows_v2/Kinect/BodyIndexFrameSource_Class/Properties/IsActive_Property.md)                 | Indicates whether there are any active stream readers for this stream.                                                                                                              |
| [BodyIndexFrameSource.FrameDescription Property](../Reference/Kinect_for_Windows_v2/Kinect/BodyIndexFrameSource_Class/Properties/FrameDescription_Property.md) | Gives you the information you need to know about the resulting frames so that you can pre-allocate a correctly sized buffer to store frame data. Does not apply to BodyFrameStream. |
| [BodyIndexFrameSource.KinectSensor Property](../Reference/Kinect_for_Windows_v2/Kinect/BodyIndexFrameSource_Class/Properties/KinectSensor_Property.md)         | A back pointer to the sensor that this stream is exposed from.                                                                                                                      |

<span id="ID4EEH"></span>
Stream readers  
--------------  

Each stream has its own type of stream reader, but they all share the same basic functionality.  

| API element                                                                                                                                        | Description                                                                                                                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [BodyFrameReader.AcquireLatestFrame Method](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrameReader_Class/Methods/AcquireLatestFrame_Method.md)  | Gets the latest frame.                                                                                                                                                               |
| [BodyFrameReader.FrameArrived Event](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrameReader_Class/Events/FrameArrived_Event.md)                 | Subscribes to this event to be notified when new frames are available.                                                                                                               |
| [BodyFrameReader.IsPaused Property](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrameReader_Class/Properties/IsPaused_Property.md)               | Controls whether or not frames will be delivered to the users of this particular stream reader instance. This will have no effect on the stream itself or other open stream readers. |
| [BodyFrameReader.Close Method](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrameReader_Class/Methods/Close_Method.md)                            | Closes the stream reader. When the last open stream reader for a stream is closed, the stream itself will be disabled.                                                               |
| [BodyFrameReader.BodyFrameSource Property](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrameReader_Class/Properties/BodyFrameSource_Property.md) | A back pointer to the stream this reader was opened from.                                                                                                                            |

<span id="ID4EDBAC"></span>
Frames  
------  

A *frame* contains the data delivered from the sensor. Use the frame objects to copy frame data into the applications buffer or access the underlying system buffer. Each frame stores frame data temporarily to avoid memory allocation. An application should get the data out of each frame and close/dispose it as quickly as possible to free up the underlying handle and make sure that the system does not need to keep allocating new items to store incoming frame data.  

Each stream has its own frame type, but they all share the same basic functionality. While each frame does have many similarities, these are the types that are the most different between each individual stream.  

| API element                                                                                                                                   | Description                                                                                                                                                                                                                                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [DepthFrame.CopyFrameDataToArray Method](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Methods/CopyFrameDataToArray_Method.md)   | Copies the frame's pixel data to an app-provided array based buffer.                                                                                                                                                                                                                                                                            |
| [DepthFrame.CopyFrameDataToBuffer Method](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Methods/CopyFrameDataToBuffer_Method.md) | Copies the frame's pixel data to an app-provided IBuffer.                                                                                                                                                                                                                                                                                       |
| [DepthFrame.LockImageBuffer Method](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Methods/LockImageBuffer_Method.md)             | Gives application access to the underlying buffer used by the system to store this frame's data. Keeping this buffer active for long periods of time will result in the system continuously allocating new buffers for incoming streams. Attempts to write to this will fail.                                                                   |
| [DepthFrame.Close Method](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Methods/Close_Method.md)                                 | Releases the handle to the underlying system buffer. After this is called, all other operations will fail.                                                                                                                                                                                                                                      |
| [DepthFrame.DepthFrameSource Property](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Properties/DepthFrameSource_Property.md)    | A back pointer to the stream reader that provided this frame.                                                                                                                                                                                                                                                                                   |
| [DepthFrame.FrameDescription Property](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Properties/FrameDescription_Property.md)    | Provides the information the app needs to know about to allocate a buffer for this frame. Does not apply to **BodyFrame**.                                                                                                                                                                                                                      |
| [DepthFrame.RelativeTime Property](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class/Properties/RelativeTime_Property.md)            | Provides a **TimeSpan** **UInt64** that represents when this frame was created. This value does not allow you to determine the absolute, real-world time of creation, but it does allow you to know when frames were delivered in relation to each other, both within and between frames from a given Kinect sensor. Units are in milliseconds. |

<span id="ID4EDEAC"></span>
Infrared frame  
--------------  

The [InfraredFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/InfraredFrame_Class.md) provides a view of the scene that looks just like a black and white photograph, but is actively lit, so brightness is consistent regardless of location and room brightness. The infrared frame is great for computer vision algorithms where texture is important, such as facial recognition. Data is stored as 16-bit unsigned integers. The infrared frame is also great for green screening, tracking reflective markers, and filtering out low-return (and therefore jittery) depth pixels. Note that the infrared frame is derived from the same sensor as depth, so the images are perfectly aligned. For example, the infrared pixel at row 5 col 9 goes with the depth pixel at row 5 col 9.  

<span id="ID4EOEAC"></span>
Long exposure infrared frame  
----------------------------  

This frame is similar to the [InfraredFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/InfraredFrame_Class.md), except it has been exposed over a longer period of time. The result is a higher quality image, with less noise, at the expense of some motion blur for objects that are moving.  

<span id="ID4E1EAC"></span>
Depth frame  
-----------  

The [DepthFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/DepthFrame_Class.md) represents a frame where each pixel represents the distance of the closest object seen by that pixel. The data for this frame is stored as 16-bit unsigned integers, where each value represents the distance in millimeters. The maximum depth distance is 8 meters, although reliability starts to degrade at around 4.5 meters. Developers can use the depth frame to build custom tracking algorithms in cases where the [BodyFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrame_Class.md) isn’t enough.  

<span id="ID4EJFAC"></span>
Body frame  
----------  

The [BodyFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrame_Class.md) contains all the computed real-time tracking information about people that are in view of the sensor. The computed info includes skeletal joints and orientations, hand states, and more for up to 6 people at a time. These tracking features provide a great baseline for getting started with human interaction in your application. To extract this tracking data from the BodyFrame, allocate a vector of 6 body pointers and pass it to [BodyFrame.GetAndRefreshBodyData Method](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrame_Class/Methods/GetAndRefreshBodyData_Method.md). Each body in the array represents tracking information for each of the 6 possible bodies that can be tracked simultaneously. Each body that represents an actual live user in view of the sensor will be marked as tracked.  

To access the list of bodies, first allocate a vector at startup like this:  

    auto bodies = ref new Platform::Collections::Vector<Body^>(6);  

Then, for each frame, update the vector like this:  

    bodyFrame->GetAndRefreshBodyData(bodies);  

<span id="ID4EBGAC"></span>
Body index frame  
----------------  

The [BodyIndexFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/BodyIndexFrame_Class.md) represents a frame that is computed based on the depth image. This image tells you which depth or infrared pixels belong to tracked people and which belong to the background. The pixel values in this frame are 8-bit unsigned integers, where 0-5 map directly to the BodyData index in the [BodyFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrame_Class.md). Values greater than the value obtained from [BodyFrameSource.BodyCount Property](../Reference/Kinect_for_Windows_v2/Kinect/BodyFrameSource_Class/Properties/BodyCount_Property.md) indicate that the pixel is part of the background, not associated with a tracked body. This frame is useful for green screening applications, or any scenario where you want to display the silhouette of the user. It also provides good starting bounds for custom depth algorithms.  

<span id="ID4ETGAC"></span>
Color frame source  
------------------  

Color frame source extends the pattern defined in depth stream, because there are a few options to be set on the stream. Use this source to get a copy of the image frame data converted into the desired color image format (such as RGB or YUV). Regardless of the format, the pixel type will be a **UInt8** (byte). There are **CopyRaw** and **LockRaw** accessors for the different formats, as well as new **CopyConverted** accessors, which convert the raw image to the specified format in the provided buffer.  

| API element                                                                                                                                          | Description                                                                                                                                                                               |
|------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ColorFrameSource.CreateFrameDescription Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrameSource_Class/Methods/CreateFrameDescription.md) | Creates a **FrameDescription** object that describes a color frame with the provided format and resolution. This replaces the **FrameDescription** property found on other image streams. |
| [ColorFrameSource.OpenReader Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrameSource_Class/Methods/OpenReader_Method.md)                  | Opens a new stream reader. This reader must be disposed.                                                                                                                                  |
| [ColorFrame.CopyConvertedFrameDataToArray Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrame_Class/Methods/CopyConvertedFrameDataToAr.md)  | Converts the raw format into the requested format and copies the data into the array provided.                                                                                            |
| [ColorFrame.CopyConvertedFrameDataToBuffer Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrame_Class/Methods/CopyConvertedFrameDataToBu.md) | Fills provided buffers with a version of the image converted into the specified format.                                                                                                   |
| [ColorFrame.CopyRawFrameDataToArray Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrame_Class/Methods/CopyRawFrameDataToArray.md)           | Copies the raw frame data into the array provided.                                                                                                                                        |
| [ColorFrame.CopyRawFrameDataToBuffer Method](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrame_Class/Methods/CopyRawFrameDataToBuffer.md)         | Copies the raw frame data into the buffer provided.                                                                                                                                       |
| [ColorFrame.RawColorImageFormat Property](../Reference/Kinect_for_Windows_v2/Kinect/ColorFrame_Class/Properties/RawColorImageFormat_Property.md)     | Returns the color format of raw pixels.                                                                                                                                                   |

<span id="ID4ERJAC"></span>
Multisource frame  
-----------------  

The [MultiSourceFrame Class](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class.md) provides access to multiple frame types through a single interface. Obtain references to the individual frame types with the following properties:  

-   [MultiSourceFrame.BodyFrameReference Property](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class/Properties/BodyFrameReference_Property.md)  
-   [MultiSourceFrame.BodyIndexFrameReference Property](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class/Properties/BodyIndexFrameReference.md)  
-   [MultiSourceFrame.ColorFrameReference Property](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class/Properties/ColorFrameReference_Property.md)  
-   [MultiSourceFrame.DepthFrameReference Property](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class/Properties/DepthFrameReference_Property.md)  
-   [MultiSourceFrame.InfraredFrameReference Property](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class/Properties/InfraredFrameReference.md)  
-   [MultiSourceFrame.LongExposureInfraredFrameReference Property](../Reference/Kinect_for_Windows_v2/Kinect/MultiSourceFrame_Class/Properties/LongExposureInfraredFrameR.md)  

<span id="ID4EELAC"></span>

Audio data  
==========  

<span id="ID4EILAC"></span>
Audio beam frame  
----------------  

Audio data is collected from a microphone array and processed into beams that emphasize the sound from a certain direction. A beam can set to automatically track a sound source or to be aimed in a specific direction. The sound data for a beam is divided up into frames that roughly correspond to each video frame. The sound frames are sub divided into subframes that are about 16 ms long.  

The WinRT APIs for audio data from the Kinect sensor are described in the reference under [WindowsPreview.Kinect Namespace](../Reference/Kinect_for_Windows_v2/Kinect.md).  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Kinect API Overview
RLTitle : Kinect API Overview
KeywordA : O:Microsoft.Kinect.k4w_nui_winrt_overview_v2
KeywordA : 7d7f80f9-29f4-3c20-bbaa-684669d1417c
KeywordK : Kinect API Overview
KeywordK : Kinect API overview
AssetID : 7d7f80f9-29f4-3c20-bbaa-684669d1417c
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
