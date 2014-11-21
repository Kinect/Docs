IKinectPointerPointProperties Interface  
=======================================  

Provides extended properties for a [IKinectPointerPoint](IKinectPointerPoint.md) object. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IKinectPointerPointProperties : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectPointerPointProperties** has the following members.  

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
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_BodyTimeCounter_Method.md">get_BodyTimeCounter</a></td>
<td align="left">Gets a time stamp to associate the pointer with a <a href="IBody_Interface.md">IBody</a> object.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_BodyTrackingId_Method.md">get_BodyTrackingId</a></td>
<td align="left">Gets a unique identifier that associates the pointer with a <a href="IBody_Interface.md">IBody</a> object.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_HandReachExtent_Method.md">get_HandReachExtent</a></td>
<td align="left">Gets a value indicating the distance along the Z axis of the hand from the shoulder.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_HandRotation_Method.md">get_HandRotation</a></td>
<td align="left">Gets the rotation of the hand associated with the pointer point.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_HandType_Method.md">get_HandType</a></td>
<td align="left">Gets a value indicating whether the hand that is associated with the pointer is a identified as a user's right hand, left hand, or neither.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_IsEngaged_Method.md">get_IsEngaged</a></td>
<td align="left">Gets a value that indicates whether the pointer point is engaged.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_IsInRange_Method.md">get_IsInRange</a></td>
<td align="left">Gets a value that indicates whether the pointer point is in range.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_IsPrimary_Method.md">get_IsPrimary</a></td>
<td align="left">Gets a value that indicates whether the pointer is being tracked as the primary engaged user.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_PressExtent_Method.md">get_PressExtent</a></td>
<td align="left">Gets a normalized Z value for a pressing gesture.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectPointerPointPrope/Methods/get_UnclampedPosition.md">get_UnclampedPosition</a></td>
<td align="left">Gets the unclamped position of the pointer point.</td>
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
TOCTitle : IKinectPointerPointProperties Interface
RLTitle : IKinectPointerPointProperties Interface
KeywordK : IKinectPointerPointProperties interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectPointerPointProperties
KeywordF : Microsoft.Kinect.kinect.IKinectPointerPointProperties
KeywordA : T:Microsoft.Kinect.kinect.IKinectPointerPointProperties
AssetID : T:Microsoft.Kinect.kinect.IKinectPointerPointProperties
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectPointerPointProperties
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
