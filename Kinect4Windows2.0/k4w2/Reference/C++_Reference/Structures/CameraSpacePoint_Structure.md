CameraSpacePoint Structure  
==========================  

A 3D location in camera space. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>typedef struct _CameraSpacePoint {  
    float X;  
    float Y;  
    float Z;  
} CameraSpacePoint;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**X**    
The X component in camera space.  

**Y**    
The Y component in camera space.  

**Z**    
The Z component in camera space.  

<span id="remarks"></span>

Remarks  
=======  

Camera space refers to the 3D coordinate system used by Kinect. The coordinate system is defined as follows:  

-   The origin (x=0, y=0, z=0) is located at the center of the IR sensor on Kinect  
-   X grows to the sensor’s left  
-   Y grows up (note that this direction is based on the sensor’s tilt)  
-   Z grows out in the direction the sensor is facing  
-   1 unit = 1 meter  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  

<span id="ID4EWB"></span>

See also  
========  

<span id="ID4EYB"></span>
#### Reference  

[Body tracking](../../../Programming_Guide/Body_tracking.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraSpacePoint Structure
RLTitle : CameraSpacePoint Structure
KeywordK : CameraSpacePoint structure
KeywordF : CameraSpacePoint
KeywordF : Microsoft.Kinect.kinect.CameraSpacePoint
KeywordA : T:Microsoft.Kinect.kinect.CameraSpacePoint
AssetID : T:Microsoft.Kinect.kinect.CameraSpacePoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.CameraSpacePoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
