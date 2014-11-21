FaceFrameSource Class  
=====================  

Represents a face frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class FaceFrameSource sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class FaceFrameSource</code></pre></td>
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
<td align="left"><pre><code>var faceFrameSource = Microsoft.Kinect.Face.FaceFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**FaceFrameSource** has the following members.  

<span id="publicconstructorsSection"></span>

Constructors  
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
<td align="left"><a href="FaceFrameSource_Class/Constructor.md">FaceFrameSource</a></td>
<td align="left">Initializes a new instance of the FaceFrameSource class.</td>
</tr>
</tbody>
</table>

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
<td align="left"><a href="FaceFrameSource_Class/Properties/FaceFrameFeatures_Property.md">FaceFrameFeatures</a></td>
<td align="left">Gets the flags that indicate which face frame features data are present in this face frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceFrameSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets the current activity status of this source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="FaceFrameSource_Class/Properties/IsTrackingIdValid_Property.md">IsTrackingIdValid</a></td>
<td align="left">Gets a boolean that indicates if the tracking id is valid.</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceFrameSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the Kinect sensor associated with the face frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="FaceFrameSource_Class/Properties/TrackingId_Property.md">TrackingId</a></td>
<td align="left">Gets or sets the tracking id.</td>
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
<td align="left"><a href="FaceFrameSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Opens a new stream reader. This reader must be disposed.</td>
</tr>
</tbody>
</table>

<span id="publiceventsSection"></span>

Events  
======  

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
<td align="left"><a href="FaceFrameSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">FaceFrameSource</a> changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceFrameSource_Class/Events/TrackingIdLost_Event.md">TrackingIdLost</a></td>
<td align="left">This event occurs when invalid frames arrive for the TrackingId listed in the event args.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EV"></span>

See also  
========  

<span id="ID4EX"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameSource Class
RLTitle : FaceFrameSource Class
KeywordK : FaceFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Face.FaceFrameSource
KeywordF : FaceFrameSource
KeywordF : Microsoft.Kinect.Face.FaceFrameSource
KeywordA : T:Microsoft.Kinect.Face.FaceFrameSource
AssetID : T:Microsoft.Kinect.Face.FaceFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameSource
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
