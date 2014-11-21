Interfaces  
==========  

<span id="ID4EM"></span>

Kinect Interfaces  
=================  

[IAudioBeam](Interfaces/IAudioBeam_Interface.md)    
Represents an audio beam.  

[IAudioBeamFrame](Interfaces/IAudioBeamFrame_Interface.md)    
Represents an audio beam frame.  

[IAudioBeamFrameArrivedEventArgs](Interfaces/IAudioBeamFrameArrivedEven.md)    
Arguments for the IAudioBeamFrame FrameReady events.  

[IAudioBeamFrameList](Interfaces/IAudioBeamFrameList.md)    
Represents a list of audio beam frames.  

[IAudioBeamFrameReader](Interfaces/IAudioBeamFrameReader.md)    
Represents an audio frame reader.  

[IAudioBeamFrameReference](Interfaces/IAudioBeamFrameReference.md)    
Represents an audio frame reference.  

[IAudioBeamList](Interfaces/IAudioBeamList_Interface.md)    
Represents a collection of audio beams.  

[IAudioBeamSubFrame](Interfaces/IAudioBeamSubFrame_Interface.md)    
Represents and audio beam sub frame.  

[IAudioBodyCorrelation](Interfaces/IAudioBodyCorrelation.md)    
Represents an AudioBodyCorrelation class which contains a body tracking id.  

[IAudioSource](Interfaces/IAudioSource_Interface.md)    
Represents an audio frame source.  

[IBody](Interfaces/IBody_Interface.md)    
Represents a body.  

[IBodyFrame](Interfaces/IBodyFrame_Interface.md)    
Represents a frame that contains all the computed real-time tracking information about people that are in view of the sensor.  

[IBodyFrameArrivedEventArgs](Interfaces/IBodyFrameArrivedEventArgs.md)    
Arguments for the body FrameReady events.  

[IBodyFrameReader](Interfaces/IBodyFrameReader_Interface.md)    
Represents an interface to a body frame source reader.  

[IBodyFrameReference](Interfaces/IBodyFrameReference.md)    
Represents an interface to a reference to an actual body frame.  

[IBodyFrameSource](Interfaces/IBodyFrameSource_Interface.md)    
Represents an interface to a body frame source.  

[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)    
Represents a pairing of a tracked body and an indicator of whether the associated hand is the right or left hand of the tracked body.  

[IBodyIndexFrame](Interfaces/IBodyIndexFrame_Interface.md)    
Represents a frame that is computed based on the depth image. This image tells you which depth or infrared pixels belong to tracked people and which belong to the background.  

[IBodyIndexFrameArrivedEventArgs](Interfaces/IBodyIndexFrameArrivedEven.md)    
Arguments for the body FrameReady events.  

[IBodyIndexFrameReader](Interfaces/IBodyIndexFrameReader.md)    
Represents an interface to a reader for body index frames.  

[IBodyIndexFrameReference](Interfaces/IBodyIndexFrameReference.md)    
An interface to a reference to an actual body frame.  

[IBodyIndexFrameSource](Interfaces/IBodyIndexFrameSource.md)    
Represents a source of body index frames from a KinectSensor.  

[IColorCameraSettings](Interfaces/IColorCameraSettings.md)    
Represents the settings of the color camera.  

[IColorFrame](Interfaces/IColorFrame_Interface.md)    
Represents a color frame for color images.  

[IColorFrameArrivedEventArgs](Interfaces/IColorFrameArrivedEventArgs.md)    
Arguments for a color frame reader's FrameArrived event.  

[IColorFrameReader](Interfaces/IColorFrameReader_Interface.md)    
Represents a reader for color frames.  

[IColorFrameReference](Interfaces/IColorFrameReference.md)    
Represents a reference to an actual color frame.  

[IColorFrameSource](Interfaces/IColorFrameSource_Interface.md)    
Represents a source of color frames from a Kinect sensor.  

[ICoordinateMapper](Interfaces/ICoordinateMapper_Interface.md)    
Represents the mapper that provides translation services from one point type to another.  

[ICoordinateMappingChangedEventArgs](Interfaces/ICoordinateMappingChangedE.md)    
Arguments for a coordinate mapping's ICoordinateMappingChanged event.  

[IDepthFrame](Interfaces/IDepthFrame_Interface.md)    
Represents a frame where each pixel represents the distance of the closest object seen by that pixel.  

[IDepthFrameArrivedEventArgs](Interfaces/IDepthFrameArrivedEventArgs.md)    
Arguments for a depth frame reader's FrameArrived event.  

[IDepthFrameReader](Interfaces/IDepthFrameReader_Interface.md)    
Represents a reader for depth frames.  

[IDepthFrameReference](Interfaces/IDepthFrameReference.md)    
Represents a reference to an actual depth frame.  

[IDepthFrameSource](Interfaces/IDepthFrameSource_Interface.md)    
Represents a source of depth frames from a KinectSensor.  

[IEnumKinectSensor](Interfaces/IEnumKinectSensor_Interface.md)    
Represents an interface to an enumeration of Kinect sensors.  

[IFrameCapturedEventArgs](Interfaces/IFrameCapturedEventArgs.md)    
Arguments for a frame source's FrameCaptured event.  

[IFrameDescription](Interfaces/IFrameDescription_Interface.md)    
Represents the properties of an image frame from the KinectSensor.  

[IGesture Interface](Interfaces/IGesture_Interface.md)    
Represents a gesture.  

[IInfraredFrame](Interfaces/IInfraredFrame_Interface.md)    
Represents a frame that provides view of the scene that looks just like a black and white photograph, but is actively lit, so brightness is consistent regardless of location and room brightness.  

[IInfraredFrameArrivedEventArgs](Interfaces/IInfraredFrameArrivedEvent.md)    
Arguments for an infrared frame reader's FrameArrived event.  

[IInfraredFrameReader](Interfaces/IInfraredFrameReader.md)    
Represents a reader for infrared frames.  

[IInfraredFrameReference](Interfaces/IInfraredFrameReference.md)    
Represents a reference to an actual infrared frame.  

[IInfraredFrameSource](Interfaces/IInfraredFrameSource.md)    
Represents a source of infrared frames from a KinectSensor.  

[IIsAvailableChangedEventArgs](Interfaces/IIsAvailableChangedEventArgs.md)    
Represents the arguments for a KinectSensor's IsAvailableChanged event.  

[IKinectCoreWindow](Interfaces/IKinectCoreWindow_Interface.md)    
Represents a Kinect for Windows app with input events and basic user interface behaviors. Only 1 core window is in “focus” at any one time, and that one gets the pointers and related events. he coordinate space of the window is normalized to the [0,1] range in both dimensions.  

[IKinectGestureRecognizer](Interfaces/IKinectGestureRecognizer.md)    
Provides gesture and manipulation recognition, and settings.  

[IKinectGestureRecognizerManipulationHandler](Interfaces/IKinectGestureRecognizerMa.md)    
Provides methods for handling Kinect manipulation events.  

[IKinectGestureRecognizerSelectionHandler](Interfaces/IKinectGestureRecognizerSe.md)    
Provides methods for handling Kinect selection gesture events.  

[IKinectHoldingEventArgs](Interfaces/IKinectHoldingEventArgs.md)    
Provides data for the Holding event.  

[IKinectManipulationCompletedEventArgs](Interfaces/IKinectManipulationComplet.md)    
Provides data for the ManipulationCompleted event.  

[IKinectManipulationInertiaStartingEventArgs](Interfaces/IKinectManipulationInertia.md)    
Provides data for the ManipulationInertiaStarting event.  

[IKinectManipulationStartedEventArgs](Interfaces/IKinectManipulationStarted.md)    
Provides data for the ManipulationStarted event.  

[IKinectManipulationUpdatedEventArgs](Interfaces/IKinectManipulationUpdated.md)    
Provides data for the ManipulationUpdated event.  

[IKinectPointerDevice](Interfaces/IKinectPointerDevice.md)    
Represents a Kinect pointer device.  

[IKinectPointerEventArgs](Interfaces/IKinectPointerEventArgs.md)    
Provides data for [IKinectCoreWindow](Interfaces/IKinectCoreWindow_Interface.md) pointer events.  

[IKinectPointerPoint](Interfaces/IKinectPointerPoint.md)    
Provides basic properties for the input pointer associated with a Kinect for Windows input.  

[IKinectPointerPointProperties](Interfaces/IKinectPointerPointPropert.md)    
Provides extended properties for a [IKinectPointerPoint](Interfaces/IKinectPointerPoint.md) object.  

[IKinectPressingCompletedEventArgs](Interfaces/IKinectPressingCompletedEv.md)    
Provides data for the PressingCompleted event.  

[IKinectPressingUpdatedEventArgs](Interfaces/IKinectPressingUpdatedEven.md)    
Provides data for the PressingUpdated event.  

[IKinectTappedEventArgs](Interfaces/IKinectTappedEventArgs.md)    
Provides data for the Tapped event.  

[IKinectSensor](Interfaces/IKinectSensor_Interface.md)    
Represents a Kinect sensor device.  

[ILongExposureInfraredFrame](Interfaces/ILongExposureInfraredFrame.md)    
Represents a long exposure infrared frame.  

[ILongExposureInfraredFrameArrivedEventArgs](Interfaces/ILongExposureInfraredFrame.md)    
Arguments for an infrared frame reader's FrameArrived event.  

[ILongExposureInfraredFrameReader](Interfaces/ILongExposureInfraredFrame.md)    
Represents a reader for long exposure infrared frames.  

[ILongExposureInfraredFrameReference](Interfaces/ILongExposureInfraredFrame.md)    
Represents a reference to an actual long exposure infrared frame.  

[ILongExposureInfraredFrameSource](Interfaces/ILongExposureInfraredFrame.md)    
Represents a source of long exposure infrared frames from a KinectSensor.  

[IMultiSourceFrame](Interfaces/IMultiSourceFrame_Interface.md)    
Represents a multi source frame from the KinectSensor.  

[IMultiSourceFrameArrivedEventArgs](Interfaces/IMultiSourceFrameArrivedEv.md)    
Arguments for a multi source frame reader's FrameArrived event.  

[IMultiSourceFrameReader](Interfaces/IMultiSourceFrameReader.md)    
Represents a reader for multi source frames.  

[IMultiSourceFrameReference](Interfaces/IMultiSourceFrameReference.md)    
Represents a reference to an actual multi source frame.  

<span id="ID4EIH"></span>

Face Interfaces  
===============  

[ICaptureStatusChangedEventArgs Interface](Interfaces/ICaptureStatusChangedEvent.md)    
Provides data for the [IFaceModelBuilder Interface](Interfaces/IFaceModelBuilder_Interface.md) CaptureStatusChanged event.  

[ICollectionStatusChangedEventArgs Interface](Interfaces/ICollectionStatusChangedEv.md)    
Provides data for the [IFaceModelBuilder Interface](Interfaces/IFaceModelBuilder_Interface.md) CollectionStatusChanged event.  

[IFaceAlignment Interface](Interfaces/IFaceAlignment_Interface.md)    
Stores face alignment data.  

[IFaceFrame Interface](Interfaces/IFaceFrame_Interface.md)    
Represents face frame points.  

[IFaceFrameArrivedEventArgs Interface](Interfaces/IFaceFrameArrivedEventArgs.md)    
Arguments for FaceFrameReader events.  

[IFaceFrameReader Interface](Interfaces/IFaceFrameReader_Interface.md)    
Represents a reader for face frames.  

[IFaceFrameReference Interface](Interfaces/IFaceFrameReference.md)    
Represents a reference to an actual face frame.  

[IFaceFrameResult Interface](Interfaces/IFaceFrameResult_Interface.md)    
Represents a face frame result.  

[IFaceFrameSource Interface](Interfaces/IFaceFrameSource_Interface.md)    
Represents a FaceFrameSource.  

[IFaceModel Interface](Interfaces/IFaceModel_Interface.md)    
Represents a face model.  

[IFaceModelBuilder Interface](Interfaces/IFaceModelBuilder_Interface.md)    
Represents a face model builder.  

[IFaceModelData Interface](Interfaces/IFaceModelData_Interface.md)    
Represents face model data.  

[IHighDefinitionFaceFrame Interface](Interfaces/IHighDefinitionFaceFrame.md)    
Represents a high definition face frame.  

[IHighDefinitionFaceFrameArrivedEventArgs Interface](Interfaces/IHighDefinitionFaceFrameAr.md)    
Arguments for high definition face frame events.  

[IHighDefinitionFaceFrameReader Interface](Interfaces/IHighDefinitionFaceFrameRe.md)    
Represents a high definition face frame reader.  

[IHighDefinitionFaceFrameReference Interface](Interfaces/IHighDefinitionFaceFrameRe.md)    
Represents a reference to an actual high definition face frame.  

[IHighDefinitionFaceFrameSource Interface](Interfaces/IHighDefinitionFaceFrameSo.md)    
Represents a high definition face frame source.  

[ITrackingIdLostEventArgs Interface](Interfaces/ITrackingIdLostEventArgs.md)    
Provides data for the TrackingIdLost event.  

<span id="ID4EEBAC"></span>

Fusion Interfaces  
=================  

[INuiFusionCameraPoseFinder Interface](Interfaces/INuiFusionCameraPoseFinder.md)    
Encapsulates camera pose finder creation, updating, and pose-finding functions.  

[INuiFusionColorMesh Interface](Interfaces/INuiFusionColorMesh.md)    
The INuiFusionColorMesh object is created when meshing a reconstruction volume. This provides access to the vertices, vertex colors, and triangle indexes of the mesh.  

[INuiFusionColorReconstruction Interface](Interfaces/INuiFusionColorReconstruct.md)    
Encapsulates reconstruction volume creation, updating, and meshing functions with color.  

[INuiFusionMatchCandidates Interface](Interfaces/INuiFusionMatchCandidates.md)    
Used by the CameraPoseFinder::FindCameraPose method to provide access to the matched camera poses and their similarity measurements.  

[INuiFusionMesh Interface](Interfaces/INuiFusionMesh_Interface.md)    
The Mesh object is created when meshing a reconstruction volume. This provides access to the vertices, normals, and triangle indexes of the mesh.  

[INuiFusionReconstruction Interface](Interfaces/INuiFusionReconstruction.md)    
Reconstruction encapsulates reconstruction volume creation updating and meshing functions.  

<span id="ID4E2BAC"></span>

Visual Gesture Builder Interfaces  
=================================  

[IContinuousGestureResult Interface](Interfaces/IContinuousGestureResult.md)    
Provides information about the progress of a continuous gesture result.  

[IDiscreteGestureResult Interface](Interfaces/IDiscreteGestureResult.md)    
Provides methods for determining the status of a discrete gesture detection.  

[ITrackingIdLostEventArgs Interface](Interfaces/ITrackingIdLostEventArgs.md)    
Provides data for the TrackingIdLost event.  

[IVisualGestureBuilderDatabase Interface](Interfaces/IVisualGestureBuilderDatab.md)    
Represents a gesture data store.  

[IVisualGestureBuilderFrame Interface](Interfaces/IVisualGestureBuilderFrame.md)    
Represents a Visual Gesture Builder frame.  

[IVisualGestureBuilderFrameArrivedEventArgs Interface](Interfaces/IVisualGestureBuilderFrame.md)    
Provides data for the FrameArrived event.  

[IVisualGestureBuilderFrameReader Interface](Interfaces/IVisualGestureBuilderFrame.md)    
Represents a Visual Gesture Builder frame reader.  

[IVisualGestureBuilderFrameReference Interface](Interfaces/IVisualGestureBuilderFrame.md)    
Represents a reference to an actual Visual Gesture Builder frame.  

[IVisualGestureBuilderFrameSource Interface](Interfaces/IVisualGestureBuilderFrame.md)    
Represents a Visual Gesture Builder frame source.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Interfaces
RLTitle : Interfaces
KeywordA : O:Microsoft.Kinect.kinect.k4w_ref_interfaces
KeywordA : f04e3517-a874-fb84-a627-a3bdbe83d897
KeywordK : Interfaces
AssetID : f04e3517-a874-fb84-a627-a3bdbe83d897
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
