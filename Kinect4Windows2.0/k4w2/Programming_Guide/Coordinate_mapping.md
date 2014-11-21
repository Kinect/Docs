Coordinate mapping  
==================  

This topic explains how to use coordinate mapping to project Kinect data between coordinate spaces.  
-   [The CoordinateMapper class](#ID4ER)  
-   [Camera space](#ID4EDB)  
-   [Depth space](#ID4E5B)  
-   [Color space](#ID4ELC)  

<span id="ID4ER"></span>

The CoordinateMapper class  
==========================  

The [CoordinateMapper Class](../Reference/Kinect_for_Windows_v2/Kinect/CoordinateMapper_Class.md) is used to perform two tasks:  

-   Project and unproject depth from 2D image space to 3D camera space  
-   Map between locations on the depth image and their corresponding locations on the color image  

<span id="ID4EDB"></span>

Camera space  
============  

Camera space refers to the 3D coordinate system used by Kinect. The coordinate system is defined as follows:  

-   The origin (x=0, y=0, z=0) is located at the center of the IR sensor on Kinect  
-   X grows to the sensor’s left  
-   Y grows up (note that this direction is based on the sensor’s tilt)  
-   Z grows out in the direction the sensor is facing  
-   1 unit = 1 meter  

**Figure 1.  The camera space coordinate system**  

![](../../resources/k4w_camera_space.png)  
Note that this is a “right-handed” coordinate system, and is similar to how you might define a camera space (a.k.a. view space) in computer graphics.  

Any Kinect Tracking algorithm that operates in 3D (e.g. Skeletal Tracking) stores its results in camera space. In some cases, you might want to project one of these points to a row/column location on the depth image for further processing. In that case, you would be mapping from camera space to depth space.  

<span id="ID4E5B"></span>

Depth space  
===========  

Depth space is the term used to describe a 2D location on the depth image. Think of this as a row/column location of a pixel where x is the column and y is the row. So x=0, y=0 corresponds to the top left corner of the image and x=511, y=423 (width-1, height-1) is the bottom right corner of the image. In some cases, a z value is needed to map out of depth space. For these cases, simply sample the depth image at the row/column in question, and use that value (which is depth in millimeters) directly as z.  

A common operation on the depth image is to generate a 3D point cloud of the scene. In this case, you would be un-projecting from depth space to camera space. Note that it’s pretty expensive to call the coordinate mapping function once per pixel for the entire depth image, so you’ll want to do it in bulk. Either use one of the array-based functions (e.g. MapDepthPointsToCameraSpace) or grab the mapping table (GetDepthFrameToCameraSpaceTable) and do the multiply yourself.  

Once you’ve got a depth pixel, you might want to know the infrared value that goes along with it. This operation is easy because depth and infrared come from the same sensor on Kinect. Just sample the same row/column on the infrared image as you did for depth.  

If you want to get the color pixel that goes along with a depth pixel, you’ll need the coordinate mapper to obtain a location in color space.  

<span id="ID4ELC"></span>

Color space  
===========  

The color sensor on Kinect is offset a bit from the sensor that generates depth and infrared. As a result, the depth sensor and the color sensor see a slightly different view of the world. If you want to find the color that corresponds to given pixel on the depth image, you’ll have to convert its position to color space. To color space describes a 2D point on the color image, just like depth space does for the depth image. So a position in color space is a row/column location of a pixel on the image, where x=0, y=0 is the pixel at the top left of the color image, and x=1919, y=1079 (width-1, height-1) corresponds to the bottom right.  

Mapping from depth space to color space is a common operation for apps that want to generate a 2D color cutout of the user for greenscreening or background removal. Simply use the body index image to identify which depth pixels go with the user, and then use the coordinate mapper to get the color value for each of those pixels.  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Coordinate mapping
RLTitle : Coordinate mapping
KeywordA : O:Microsoft.Kinect.k4w_pguide_coordinatemapping
KeywordA : 00c3a5c5-43f0-fbdb-0df3-301cc9468a6e
KeywordK : Coordinate mapping
KeywordK : face tracking
AssetID : 00c3a5c5-43f0-fbdb-0df3-301cc9468a6e
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
