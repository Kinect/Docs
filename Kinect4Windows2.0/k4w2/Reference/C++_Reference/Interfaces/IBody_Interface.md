IBody Interface  
===============  

Represents a body. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBody : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBody** has the following members.  

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
<td align="left"><a href="IBody_Interface/Methods/get_ClippedEdges_Method.md">get_ClippedEdges</a></td>
<td align="left">Gets the clipped edges.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_Engaged_Method.md">get_Engaged</a></td>
<td align="left">Gets the level of user engagement.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_HandLeftConfidence.md">get_HandLeftConfidence</a></td>
<td align="left">Gets the tracking confidence for the left hand.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_HandLeftState_Method.md">get_HandLeftState</a></td>
<td align="left">Gets the left hand state.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_HandRightConfidence.md">get_HandRightConfidence</a></td>
<td align="left">Gets the tracking confidence for the right hand.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_HandRightState_Method.md">get_HandRightState</a></td>
<td align="left">Retrieves the right hand state.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_IsRestricted_Method.md">get_IsRestricted</a></td>
<td align="left">Retrieves a boolean value that indicates if the body is restricted from a full range of motion.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_IsTracked_Method.md">get_IsTracked</a></td>
<td align="left">Retrieves a boolean value that indicates if the body is tracked.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_Lean_Method.md">get_Lean</a></td>
<td align="left">Gets the amount a body is leaning, which is a number between -1 (leaning left or back) and 1 (leaning right or front).</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_LeanTrackingState_Method.md">get_LeanTrackingState</a></td>
<td align="left">Gets the lean tracking state, which indicates if the body is tracked.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">Gets the tracking ID.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/GetActivityDetectionResults.md">GetActivityDetectionResults</a></td>
<td align="left">Gets the activity detection results from IBody.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/GetAppearanceDetectionResu.md">GetAppearanceDetectionResults</a></td>
<td align="left">Gets the appearance.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/GetExpressionDetectionResu.md">GetExpressionDetectionResults</a></td>
<td align="left">Gets the dictionary of expressions. This API is not implemented in the Kinect for Windows v2 SDK and will always return null. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/GetJointOrientations_Method.md">GetJointOrientations</a></td>
<td align="left">Gets the dictionary of joint orientations.</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/GetJoints_Method.md">GetJoints</a></td>
<td align="left">Gets the dictionary of joints.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IBody Interface
RLTitle : IBody Interface
KeywordK : IBody interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBody
KeywordF : Microsoft.Kinect.kinect.IBody
KeywordA : T:Microsoft.Kinect.kinect.IBody
AssetID : T:Microsoft.Kinect.kinect.IBody
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
