KinectManipulationVelocities Structure  
======================================  

Represents the velocities of the accumulated transformations for the current interaction. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _KinectManipulationVelocities {  
    PointF Linear;  
    float Angular;  
    float Expansion;  
} KinectManipulationVelocities;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**Linear**    
The linear component of the velocity in device-independent units (1/96th inch per unit) per millisecond.  

**Angular**    
The angular component of the velocity in degrees per millisecond.  

**Expansion**    
The rate at which the manipulation is resized in device-independent units (1/96th inch per unit) per millisecond.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectManipulationVelocities Structure
RLTitle : KinectManipulationVelocities Structure
KeywordK : KinectManipulationVelocities structure
KeywordF : KinectManipulationVelocities
KeywordF : Microsoft.Kinect.kinect.KinectManipulationVelocities
KeywordA : T:Microsoft.Kinect.kinect.KinectManipulationVelocities
AssetID : T:Microsoft.Kinect.kinect.KinectManipulationVelocities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectManipulationVelocities
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
