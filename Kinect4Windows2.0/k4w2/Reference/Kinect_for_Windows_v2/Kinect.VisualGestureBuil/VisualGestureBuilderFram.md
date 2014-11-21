VisualGestureBuilderFrameSource Class  
=====================================  

Represents a visual gesture builder frame source. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class VisualGestureBuilderFrameSource sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class VisualGestureBuilderFrameSource : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var visualGestureBuilderFrameSource = Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**VisualGestureBuilderFrameSource** has the following members.  

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
<td align="left"><a href="VisualGestureBuilderFram/VisualGestureBuilderFram.md">VisualGestureBuilderFrameSource</a></td>
<td align="left">Initializes a new instance of the <a href="">VisualGestureBuilderFrameSource</a> class.</td>
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
<td align="left"><a href="VisualGestureBuilderFram/Properties/Gestures_Property.md">Gestures</a></td>
<td align="left">Gets a collection of gestures associated with the Visual Gesture Builder frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Properties/HorizontalMirror_Property.md">HorizontalMirror</a></td>
<td align="left">Gets or sets a value indicating whether horizontal mirroring should be used.</td>
</tr>
<tr class="odd">
<td align="left"><a href="VisualGestureBuilderFram/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">Gets a value indicating if the Visual Gesture Builder frame source is active.</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Properties/IsTrackingIdValid_Property.md">IsTrackingIdValid</a></td>
<td align="left">Gets or sets a value indicating if the tracking ID associated with the frame sourcec is valid.</td>
</tr>
<tr class="odd">
<td align="left"><a href="VisualGestureBuilderFram/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">Gets the Kinect sensor associated with the frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Properties/TrackingId_Property.md">TrackingId</a></td>
<td align="left">Gets or sets the tracking ID associated with the gesture frame source.</td>
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
<td align="left"><a href="VisualGestureBuilderFram/Methods/AddGesture_Method.md">AddGesture</a></td>
<td align="left">Adds the specified gesture to the Visual Gesture Builder frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Methods/AddGestures_Method.md">AddGestures</a></td>
<td align="left">Adds the specified list of gestures to the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="VisualGestureBuilderFram/Methods/Close_Method.md">Close</a></td>
<td align="left">Disposes of the object and cleans up associated resources.</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Methods/GetIsEnabled_Method.md">GetIsEnabled</a></td>
<td align="left">Gets a value indicating if the specified gesture is enabled for the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="VisualGestureBuilderFram/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">Opens a new frame reader. This reader must be disposed</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Methods/RemoveGesture_Method.md">RemoveGesture</a></td>
<td align="left">Removes the specified gesture from the Visual Gesture Builder frame source.</td>
</tr>
<tr class="odd">
<td align="left"><a href="VisualGestureBuilderFram/Methods/SetIsEnabled_Method.md">SetIsEnabled</a></td>
<td align="left">Sets whether the specified gesture is enabled for the Visual Gesture Builder frame source.</td>
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
<td align="left"><a href="VisualGestureBuilderFram/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">VisualGestureBuilderFrameSource</a> changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="VisualGestureBuilderFram/Events/TrackingIdLost_Event.md">TrackingIdLost</a></td>
<td align="left">Occurs when the tracking ID of the Visual Gesture Builder frame source is lost.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[Microsoft.Kinect.VisualGestureBuilder Namespace](../Kinect.VisualGestureBuil.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : VisualGestureBuilderFrameSource Class
RLTitle : VisualGestureBuilderFrameSource Class
KeywordK : VisualGestureBuilderFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource
KeywordF : VisualGestureBuilderFrameSource
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource
KeywordA : T:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource
AssetID : T:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource
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
