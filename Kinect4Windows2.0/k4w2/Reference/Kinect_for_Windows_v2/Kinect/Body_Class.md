Body Class  
==========  

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
<td align="left"><pre><code>public ref class Body sealed : IClosable</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public sealed class Body : IDisposable</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var body = WindowsPreview.Kinect.Body;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**Body** has the following members.  

<span id="publicpropertiesSection"></span>

Properties  
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
<td align="left"><a href="Body_Class/Properties/Activities_Property.md">Activities</a></td>
<td align="left">[Deprecated] Gets the status of the body’s possible activities. This API is not implemented in the Kinect for Windows v2 SDK and will always return null. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/Appearance_Property.md">Appearance</a></td>
<td align="left">[Deprecated] Gets the status of the body’s possible appearance characteristics. This API is not implemented in the Kinect for Windows v2 SDK and will always return null. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/ClippedEdges_Property.md">ClippedEdges</a></td>
<td align="left">Gets the edges of the field of view that clip the body.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/Engaged_Property.md">Engaged</a></td>
<td align="left">[Deprecated] Gets the status of the body’s engagement. This API is not implemented in the Kinect for Windows v2 SDK. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/Expressions_Property.md">Expressions</a></td>
<td align="left">Gets the status of the body's possible expressions. This API is not implemented in the Kinect for Windows v2 SDK and will always return null. It is included to support cross-compilation with the Xbox SDK.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/HandLeftConfidence_Property.md">HandLeftConfidence</a></td>
<td align="left">Gets the confidence of the body’s left hand state.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/HandLeftState_Property.md">HandLeftState</a></td>
<td align="left">Gets the status of the body's left hand state.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/HandRightConfidence_Property.md">HandRightConfidence</a></td>
<td align="left">Gets the confidence of the body's right hand state.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/HandRightState_Property.md">HandRightState</a></td>
<td align="left">Gets the status of the body's right hand state.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/IsRestricted_Property.md">IsRestricted</a></td>
<td align="left">Gets whether or not the body is restricted.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/IsTracked_Property.md">IsTracked</a></td>
<td align="left">Gets whether or not the body is tracked.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/JointCount_Property.md">JointCount</a></td>
<td align="left">Gets the number of joints in a body.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/JointOrientations_Property.md">JointOrientations</a></td>
<td align="left">Gets the joint orientations of the body.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/Joints_Property.md">Joints</a></td>
<td align="left">Gets the joint positions of the body.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/Lean_Property.md">Lean</a></td>
<td align="left">Gets the lean vector of the body.</td>
</tr>
<tr class="even">
<td align="left"><a href="Body_Class/Properties/LeanTrackingState_Property.md">LeanTrackingState</a></td>
<td align="left">Gets the tracking state for the body lean.</td>
</tr>
<tr class="odd">
<td align="left"><a href="Body_Class/Properties/TrackingId_Property.md">TrackingId</a></td>
<td align="left">Gets the tracking ID for the body.</td>
</tr>
</tbody>
</table>

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
<td align="left"><a href="Body_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the body.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Body Class
RLTitle : Body Class
KeywordK : Body class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.Body
KeywordF : Body
KeywordF : WindowsPreview.Kinect.Body
KeywordA : T:WindowsPreview.Kinect.Body
AssetID : T:WindowsPreview.Kinect.Body
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Body
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
