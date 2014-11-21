IKinectManipulationCompletedEventArgs::get\_Velocities Method  
=============================================================  

Gets values that indicate the velocities of the transformation deltas (translation, rotation, scale) for a manipulation at the ManipulationCompleted event. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
HRESULT get_Velocities(  
         KinectManipulationVelocities *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: KinectManipulationVelocities  
[out] The velocities of the accumulated transformations since a ManipulationStarted event.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

Velocity is the distance an object travels in a specified direction during a unit of time.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_Velocities Method
RLTitle : IKinectManipulationCompletedEventArgs::get_Velocities Method
KeywordK : get_Velocities method
KeywordK : IKinectManipulationCompletedEventArgs::get_Velocities method
KeywordF : IKinectManipulationCompletedEventArgs::get_Velocities
KeywordF : get_Velocities
KeywordF : Microsoft.Kinect.kinect.IKinectManipulationCompletedEventArgs.get_Velocities(KinectManipulationVelocities@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectManipulationCompletedEventArgs.get_Velocities(KinectManipulationVelocities@)
AssetID : M:Microsoft.Kinect.kinect.IKinectManipulationCompletedEventArgs.get_Velocities(KinectManipulationVelocities@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectManipulationCompletedEventArgs::get_Velocities
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
