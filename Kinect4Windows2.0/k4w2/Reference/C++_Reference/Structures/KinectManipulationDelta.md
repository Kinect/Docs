KinectManipulationDelta Structure  
=================================  

Represents the accumulated transformations for the current manipulation. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _KinectManipulationDelta {  
    PointF Translation;  
    float Scale;  
    float Rotation;  
    float Expansion;  
} KinectManipulationDelta;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**Translation**    
The change in x and y screen coordinates, in the core window coordinate space (normalized [0,1]).  

**Scale**    
The multiplicative change in zoom factor.  

**Rotation**    
The change in angle of rotation, in degrees. This will always be 0.  

**Expansion**    
Manipulation expansion delta. This will always be 0.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectManipulationDelta Structure
RLTitle : KinectManipulationDelta Structure
KeywordK : KinectManipulationDelta structure
KeywordF : KinectManipulationDelta
KeywordF : Microsoft.Kinect.kinect.KinectManipulationDelta
KeywordA : T:Microsoft.Kinect.kinect.KinectManipulationDelta
AssetID : T:Microsoft.Kinect.kinect.KinectManipulationDelta
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectManipulationDelta
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
