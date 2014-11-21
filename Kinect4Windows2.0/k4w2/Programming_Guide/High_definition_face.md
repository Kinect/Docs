High definition face tracking  
=============================  

The high definition face tracking API supports two primary scenarios that help get players in the game and create a stronger emotional connection between the players and the game.  

-   Face capture — Use the API to get the shape of a player’s face. The API will tell a game developer where the person needs to be in the camera view, the quality of the frames it captures, and when it has enough valid frames will calculate the shape of the user’s face and provide a game developer with those shape values. The game developer can then use those values to influence their game character design (e.g. make the player’s in-game character look more like the player).  
-   Face tracking — Use the API to get real time facial expressions of the user to animate the in-game player’s character. For each frame, a developer will get the animation units that relate to the player’s facial movements. This can be applied either to a game character that has been shaped to look like the player, or to a generic game avatar that does not look like the player. This can be used with or without face capture.  

<span id="ID4E1"></span>

Inputs  
======  

The WinRT APIs gather their inputs automatically. When the developer starts a face capture or subscribes to a face tracking stream, the WinRT API provides the Kinect color, depth, and IR images as input to the FaceModelBuilder or high definition face tracking.  

The tracking quality may be affected by the image quality of these input frames (that is, darker or fuzzier frames track worse than brighter or sharp frames). Also, larger or closer faces are tracked better than smaller faces. The API will track only those frames for which the NUI skeleton has already identified the head and neck joints.  

The tracking quality increases if the face has been captured, and the output of the capture used to initialize the face tracking. This enables the face tracker to use the precise geometry of the face instead of an average geometry, and results in more accurate characterization of face motions.  

<span id="ID4EFB"></span>

Outputs  
=======  

The face capture API outputs a face shape, defined as a set of parameters applied to the face model. The parameters are a scale factor indicating the size of the face, and a set of shape unit (SU) weights indicating how the face shape differs from the average shape. The SUs estimate the particular shape of the user’s head: the shape of features like brow, nose, cheeks, mouth, or chin.  

During face tracking, the API outputs a face orientation, a head pivot point, and a list of animation units (AUs).  

The AUs are deltas from the neutral shape that you can use to morph targets on animated avatar models so that the avatar acts as the tracked user does. For example, AUs define whether the mouth is open, the eyebrow is raised, and other details of facial expression.  

<span id="ID4EPB"></span>
Orientation and location  
------------------------  

The face orientation returned by high definition face tracking is a quaternion with the same interpretation as the [FaceRotationQuaternion](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrameResult_Class/Properties/FaceRotationQuaternion.md) property.  

The head pivot point is the computed center of the head, which the face may be rotated around. This point is defined in the Kinect body coordinate system. The origin is located at the camera’s optical center (sensor), Z axis is pointing towards a user, and Y axis is pointing up and X axis is to the right. The unit of measure is in meters. The head pivot point is comparable to the head joint of the NUI skeleton, but the head pivot point has a different vertical coordinate (suitable as a center of rotation).  

<span id="ID4E4B"></span>
Animation Units  
---------------  

The API tracks 17 animation units (AUs). Most of the AUs are expressed as a numeric weight varying between 0 and 1. Three of them, Jaw Slide Right, Right Eyebrow Lowerer, and Left Eyebrow Lowerer, vary between -1 and +1.  

The AU indices are expressed in the [FaceShapeAnimations Enumeration](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceShapeAnimations.md). The number and meaning of the AUs are subject to change.  

<span id="ID4EKC"></span>
Shape Units  
-----------  

There are more than 70 shape units (SUs). Each SU is expressed as a numeric weight that typically varies between -2 and +2, but may go outside that range.  

For a complete list of SUs, see the [FaceShapeDeformations Enumeration](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceShapeDeformations.md). The number and meaning of the SUs are subject to change.  

<span id="ID4EXC"></span>
Face Model  
----------  

You can optionally read the 3D face model computed by face capture, including every vertex and triangle in the mesh.  

Several of the mesh vertices have declared meanings, such as the tip of the nose and the outer corner of the right eye. For a complete list of high detail face points, see the [HighDetailFacePoints Enumeration](../Reference/Kinect_for_Windows_v2/Kinect.Face/HighDetailFacePoints.md).  

The vertices are comparable in purpose to the properties of the [FaceFrame Class](../Reference/Kinect_for_Windows_v2/Kinect.Face/FaceFrame_Class.md). It is not recommended that you render the tracking model onscreen, except for debugging.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : High definition face tracking
RLTitle : High definition face tracking
KeywordA : O:Microsoft.Kinect.k4w_nui_faceHD_overview
KeywordA : db699612-8acc-65a8-67f9-3092e38261b9
KeywordK : High definition face tracking
AssetID : db699612-8acc-65a8-67f9-3092e38261b9
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
