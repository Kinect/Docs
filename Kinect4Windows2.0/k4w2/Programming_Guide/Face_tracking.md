Face tracking  
=============  

This topic provides an overview of the programming model for Kinect face tracking.  
-   [The FaceFrame Object](#ID4ER)  
-   [FaceFrameResult object](#ID4E3)  
-   [FaceFrame data](#ID4EIB)  
-   [Bounding box data](#ID4E3B)  
-   [Point data](#ID4EMC)  
-   [FaceRotationQuaternion](#ID4E3C)  
-   [Face properties](#ID4EID)  
-   [Database files](#ID4EIH)  
-   [Performance considerations](#ID4EPH)  

<span id="ID4ER"></span>

The FaceFrame Object  
====================  

The [FaceFrame Class](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrame_Class.md) provides a basic set of information about a tracked body's face. It can tell you where the face is, where it is looking, basic expressive information, and if the face has glasses. All of this information can be computed against each tracked body up to a distance of 3.5 meters.  

<span id="ID4E3"></span>

FaceFrameResult object  
======================  

[FaceFrameResult Class](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class.md) is the object that provides the basic set of info on a tracked body's face and has data computed in infrared and mapped in color.  

<span id="ID4EIB"></span>

FaceFrame data  
==============  

All [FaceFrame Class](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrame_Class.md) data is computed in infrared and then mapped to color for your convenience. This means that results like the [FaceFrameResult.FaceBoundingBoxInColorSpace Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceBoundingBoxInColorSpace.md) feature are limited to the IR field of view. It also means that all information can be returned in almost any lighting condition where the IR Stream is visible, such as indoors, at night, etc. The only exceptions to this are the RightEyeClosed and LeftEyeClosed [FaceFrameResult.FaceProperties Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceProperties_Property.md) which rely on the color feed and negatively impacted by poor lighting conditions.  

<span id="ID4E3B"></span>

Bounding box data  
=================  

Face detection results include a bounding box, which is a rectangle that contains the user's head, as determined by our face detection algorithms. The bounding box is retrieved with either [FaceFrameResult.FaceBoundingBoxInColorSpace Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceBoundingBoxInColorSpace.md) or [FaceFrameResult.FaceBoundingBoxInInfraredSpace Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceBoundingBoxInInfraredS.md).  

<span id="ID4EMC"></span>

Point data  
==========  

Point data is retrieved with either [FaceFrameResult.FacePointsInColorSpace Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FacePointsInColorSpace.md) or [FaceFrameResult.FacePointsInInfraredSpace Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FacePointsInInfraredSpace.md). Sometimes called alignment points, these locations represent five landmark locations on a user’s face. The five points are the left eye, right eye, nose and, right and left mouth corners.  

<span id="ID4E3C"></span>

FaceRotationQuaternion  
======================  

The head pivot point, obtained through the [FaceRotationQuaternion](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceRotationQuaternion.md) property, is the computed center of the head, which the face may be rotated around. This point is defined in the Kinect body coordinate system. The origin is located at the camera’s optical center (sensor), Z axis is pointing towards a user, and Y axis is pointing up. The unit of measurement is in meters. The head pivot point is comparable to the head joint of the body, but the head pivot point has a different vertical coordinate (suitable as a center of rotation).  

<span id="ID4EID"></span>

Face properties  
===============  

The [FaceFrameResult.FaceProperties Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceProperties_Property.md) returns a read-only map of key/value pairs that provide information about the appearance or state of a user's face. For each entry in this map, the key is a member of the [FaceProperty Enumeration](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceProperty_Enumeration.md). The following table lists the properties that are available. Note that these classifiers were trained assuming that the Kinect is placed above or below a content source (TV, etc.), centered and oriented towards the user.  

| Property       | Description                                                                                                                                                                                                                                                            |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Happy          | The user appears to be smiling and is putting forward a happy expression. This will also pick up smiles during laughter. It’s important to note that some users appear happy even when they are not, so this should not be considered an exact translation to emotion. |
| Engaged        | Combines results from LookingAway and Eye Closed to determine if user is engaged with content.                                                                                                                                                                         |
| WearingGlasses | The user is wearing glasses.                                                                                                                                                                                                                                           |
| LeftEyeClosed  | The user's left eye is closed.                                                                                                                                                                                                                                         |
| RightEyeClosed | The user's right eye is closed.                                                                                                                                                                                                                                        |
| MouthOpen      | The user's mouth is open.                                                                                                                                                                                                                                              |
| MouthMoved     | The user's mouth moved. This is the only property that needs frame over frame results to make an accurate determination. This feature works best if the user's head is mostly still.                                                                                   |
| LookingAway    | Determines if the user is looking away from the content. The detection is not refined enough to detect slight eye gaze shifts but it will detect larger head movements like looking over to talk to someone or looking down to check your phone.                       |

For each entry in the [FaceFrameResult.FaceProperties Property](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceProperties_Property.md) map, the value is a member of the [DetectionResult Enumeration](../Reference/Kinect_for_Windows_v2/Kinect/DetectionResult_Enumeration.md) that indicates the system's detection result for the corresponding face property. The following table describes how those results are tuned and calculated in this context.  

| DetectionResult | Description                                                                                                                                                                                                                     |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Yes             | We are very certain that the property is true and you could take a destructive action on this result.                                                                                                                           |
| No              | We are very certain that the property is false and you could take a destructive action on this result.                                                                                                                          |
| Maybe           | We are pretty sure that the property is true. You could reward the user or give a positive action for this result. For most properties, you could potentially infer from this result that the corresponding movement was small. |
| Unknown         | We don’t have enough information to make a determination. This typically occurs because the user has orientated their face away from the sensor and we don’t want to give a bad result.                                         |

<span id="ID4EIH"></span>

Database files  
==============  

Every application that uses Microsoft.Kinect.Face.dll must be packaged with the NuiDatabase folder that shipped with Microsoft.Kinect.Face.dll. The face dll is only guaranteed to work with the specific NuiDatabase folder that it shipped with. The face APIs are designed to load database files from the NuiDatabase folder upon initialization and will look for the folder in the same location as Microsoft.Kinect.Face.dll.  

<span id="ID4EPH"></span>

Performance considerations  
==========================  

If a long running task (greater than the amount of time it takes for a frame to arrive) is to be performed inside an event handler all relevant frame references must be acquired prior to executing the task. If the references are not acquired beforehand, the frame data may be overwritten and calls to acquire references and / or data will return null.  

In general, it is best to avoid putting long running tasks inside event handlers and instead use separate threads to perform this work.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Face tracking
RLTitle : Face tracking
KeywordA : O:Microsoft.Kinect.k4w_pguide_facetracking_v2
KeywordA : 71e007a6-7e7d-b61c-e193-beeb0337a82e
KeywordK : Face tracking
KeywordK : face tracking
AssetID : 71e007a6-7e7d-b61c-e193-beeb0337a82e
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
