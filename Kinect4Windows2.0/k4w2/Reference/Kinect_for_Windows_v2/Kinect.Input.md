WindowsPreview.Kinect.Input Namespace  
=====================================  

Provides support for the Kinect for Windows input system. <span id="classesSection"></span>

Classes  
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
<td align="left"><a href="Kinect.Input/BodyHandPair_Class.md">BodyHandPair</a></td>
<td align="left">Represents a pairing of a tracked body and an indicator of whether the associated hand is the right or left hand of the tracked body.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectCoreWindow_Class.md">KinectCoreWindow</a></td>
<td align="left">Represents a Kinect for Windows app with input events and basic user interface behaviors. Only 1 core window is in “focus” at any one time, and that one gets the pointers and related events. The coordinate space of the window is normalized to the [0,1] range in both dimensions.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectGestureRecognizer.md">KinectGestureRecognizer</a></td>
<td align="left">Provides gesture and manipulation recognition, and settings.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectHoldingEventArgs_Class.md">KinectHoldingEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/Holding_Event.md">Holding</a> event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectManipulationComplete.md">KinectManipulationCompletedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/ManipulationCompleted_Event.md">ManipulationCompleted</a> event.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectManipulationInertiaS.md">KinectManipulationInertiaStartingEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/ManipulationInertiaStarting.md">ManipulationInertiaStarting</a> event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/ManipulationStarted_Event.md">ManipulationStarted</a> event.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/ManipulationUpdated_Event.md">ManipulationUpdated</a> event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectPointerDevice_Class.md">KinectPointerDevice</a></td>
<td align="left">Represents a Kinect pointer device.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectPointerEventArgs_Class.md">KinectPointerEventArgs</a></td>
<td align="left">Provides data for <a href="Kinect.Input/KinectCoreWindow_Class.md">KinectCoreWindow</a> pointer events.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a></td>
<td align="left">Provides basic properties for the input pointer associated with a Kinect for Windows input.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectPointerPointProperties.md">KinectPointerPointProperties</a></td>
<td align="left">Provides extended properties for a <a href="Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a> object.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectPointerPointTransform.md">KinectPointerPointTransform</a></td>
<td align="left">Represents a Kinect pointer point transform.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectPressingCompletedEve.md">KinectPressingCompletedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/PressingCompleted_Event.md">PressingCompleted</a> event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectPressingStartedEvent.md">KinectPressingStartedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/PressingStarted_Event.md">PressingStarted</a> event.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectPressingUpdatedEvent.md">KinectPressingUpdatedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/PressingUpdated_Event.md">PressingUpdated</a> event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectTappedEventArgs_Class.md">KinectTappedEventArgs</a></td>
<td align="left">Provides data for the <a href="Kinect.Input/KinectGestureRecognizer/Events/Tapped_Event.md">Tapped</a> event.</td>
</tr>
</tbody>
</table>

<span id="interfacesSection"></span>

Interfaces  
==========  

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
<td align="left"><a href="Kinect.Input/IKinectPointerPointTransform.md">IKinectPointerPointTransform</a></td>
<td align="left">Provides generalized transformation support for objects.</td>
</tr>
</tbody>
</table>

<span id="structuresSection"></span>

Structures  
==========  

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
<td align="left"><a href="Kinect.Input/KinectManipulationDelta.md">KinectManipulationDelta</a></td>
<td align="left">Represents the accumulated transformations for the current manipulation.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectManipulationVelocities.md">KinectManipulationVelocities</a></td>
<td align="left">Represents the velocities of the accumulated transformations for the current interaction.</td>
</tr>
</tbody>
</table>

<span id="enumerationsSection"></span>

Enumerations  
============  

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
<td align="left"><a href="Kinect.Input/HandType_Enumeration.md">HandType</a></td>
<td align="left">Enumerates the ways in which a hand can be identified.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectEngagementMode.md">KinectEngagementMode</a></td>
<td align="left">Enumerates the modes in which engaged users can be tracked.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectGestureSettings.md">KinectGestureSettings</a></td>
<td align="left">Specifies the interactions that are supported by an Kinect for Windows application.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/KinectHoldingState.md">KinectHoldingState</a></td>
<td align="left">Specifies the state of the <a href="Kinect.Input/KinectGestureRecognizer/Events/Holding_Event.md">Holding</a> event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Kinect.Input/KinectInteractionMode.md">KinectInteractionMode</a></td>
<td align="left">Gesture interaction modes, which determine how gestures are handled.</td>
</tr>
<tr class="even">
<td align="left"><a href="Kinect.Input/PointerDeviceType.md">PointerDeviceType</a></td>
<td align="left">Specifies the pointer device type.</td>
</tr>
</tbody>
</table>



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : WindowsPreview.Kinect.Input
RLTitle : WindowsPreview.Kinect.Input Namespace
KeywordF : WindowsPreview.Kinect.Input
KeywordA : N:WindowsPreview.Kinect.Input
KeywordK : WindowsPreview.Kinect.Input Namespace
AssetID : N:WindowsPreview.Kinect.Input
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
