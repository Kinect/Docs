IKinectManipulationUpdatedEventArgs Interface  
=============================================  

Provides data for the ManipulationUpdated event. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IKinectManipulationUpdatedEventArgs : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectManipulationUpdatedEventArgs** has the following members.  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IKinectManipulationUpdated/Methods/get_Cumulative_Method.md">get_Cumulative</a></td>
<td align="left">Gets values that indicate the accumulated transformation deltas (translation, rotation, scale) for a manipulation from the beginning of the interaction to the ManipulationUpdated event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectManipulationUpdated/Methods/get_Delta_Method.md">get_Delta</a></td>
<td align="left">Gets values that indicate the changes in the transformation deltas (translation, rotation, scale) of a manipulation since the last manipulation event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectManipulationUpdated/Methods/get_PointerDeviceType_Method.md">get_PointerDeviceType</a></td>
<td align="left">Gets the device type of the input source.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectManipulationUpdated/Methods/get_Position_Method.md">get_Position</a></td>
<td align="left">Gets the location of the pointer associated with the manipulation for the last manipulation event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectManipulationUpdated/Methods/get_Velocities_Method.md">get_Velocities</a></td>
<td align="left">Gets values that indicate the velocities of the transformation deltas (translation, rotation, scale) for a manipulation at the ManipulationUpdated event.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IKinectManipulationUpdatedEventArgs Interface
RLTitle : IKinectManipulationUpdatedEventArgs Interface
KeywordK : IKinectManipulationUpdatedEventArgs interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectManipulationUpdatedEventArgs
KeywordF : Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs
KeywordA : T:Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs
AssetID : T:Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectManipulationUpdatedEventArgs
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
