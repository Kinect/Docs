HighDefinitionFaceFrameSource Class  
===================================  

Represents a high-definition face frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class HighDefinitionFaceFrameSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class HighDefinitionFaceFrameSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var highDefinitionFaceFrameSource = Microsoft.Kinect.Face.HighDefinitionFaceFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**HighDefinitionFaceFrameSource** has the following members.  

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
<td align="left"><a href="HighDefinitionFaceFrameSou/HighDefinitionFaceFrameSou.md">HighDefinitionFaceFrameSource</a></td>
<td align="left">Initializes a new instance of the HighDefinitionFaceFrameSource class.</td>
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
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/FaceModel_Property.md">FaceModel</a></td>
<td align="left">Gets the face model for the frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets a boolean that indicates the activity state of the high-definition face frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/IsOnline_Property.md">IsOnline</a></td>
<td align="left">Gets the current activity status of this source.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/IsTrackingIdValid_Property.md">IsTrackingIdValid</a></td>
<td align="left">Gets a boolean that indicates if the tracking id is valid.</td>
</tr>
<tr class="odd">
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the Kinect sensor.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/TrackingId_Property.md">TrackingId</a></td>
<td align="left">Gets or sets the tracking ID.</td>
</tr>
<tr class="odd">
<td align="left"><a href="HighDefinitionFaceFrameSou/Properties/TrackingQuality_Property.md">TrackingQuality</a></td>
<td align="left">Gets or sets the tracking quality.</td>
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
<td align="left"><a href="HighDefinitionFaceFrameSou/Methods/FeedAndCalculateFrameData.md">FeedAndCalculateFrameData</a></td>
<td align="left">TBD</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameSou/Methods/OpenModelBuilder_Method.md">OpenModelBuilder</a></td>
<td align="left">Opens a new model builder. The model builder must be disposed.</td>
</tr>
<tr class="odd">
<td align="left"><a href="HighDefinitionFaceFrameSou/Methods/OpenReader_Method.md">OpenReader</a></td>
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
<td align="left"><a href="HighDefinitionFaceFrameSou/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">HighDefinitionFaceFrameSource</a> changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameSou/Events/TrackingIdLost_Event.md">TrackingIdLost</a></td>
<td align="left">Occurs when the tracking ID is lost.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E1"></span>

See also  
========  

<span id="ID4E3"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HighDefinitionFaceFrameSource Class
RLTitle : HighDefinitionFaceFrameSource Class
KeywordK : HighDefinitionFaceFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource
KeywordF : HighDefinitionFaceFrameSource
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource
KeywordA : T:Microsoft.Kinect.Face.HighDefinitionFaceFrameSource
AssetID : T:Microsoft.Kinect.Face.HighDefinitionFaceFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameSource
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
