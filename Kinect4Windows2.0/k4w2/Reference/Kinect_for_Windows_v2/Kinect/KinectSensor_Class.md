KinectSensor Class  
==================  

Represents a KinectSensor device. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class KinectSensor sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class KinectSensor : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var kinectSensor = WindowsPreview.Kinect.KinectSensor;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**KinectSensor** has the following members.  

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
<td align="left"><a href="KinectSensor_Class/Properties/AudioSource_Property.md">AudioSource</a></td>
<td align="left">Gets the source for audio frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/BodyFrameSource_Property.md">BodyFrameSource</a></td>
<td align="left">Gets the source for body frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/BodyIndexFrameSource.md">BodyIndexFrameSource</a></td>
<td align="left">Gets the source for body index frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/ColorFrameSource_Property.md">ColorFrameSource</a></td>
<td align="left">Gets the source for color frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/CoordinateMapper_Property.md">CoordinateMapper</a></td>
<td align="left">Gets the coordinate mapper.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/DepthFrameSource_Property.md">DepthFrameSource</a></td>
<td align="left">Gets the source for depth frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/InfraredFrameSource_Property.md">InfraredFrameSource</a></td>
<td align="left">Gets the source for infrared frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/IsAvailable_Property.md">IsAvailable</a></td>
<td align="left">Gets whether the Kinect sensor is available and able to retrieve frames.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/IsOpen_Property.md">IsOpen</a></td>
<td align="left">Gets whether or not the KinectSensor is open.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/KinectCapabilities_Property.md">KinectCapabilities</a></td>
<td align="left">Gets the capabilities of the KinectSensor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/LongExposureInfraredFrameS.md">LongExposureInfraredFrameSource</a></td>
<td align="left">Gets the source for long exposure infrared frames.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/Sensors_Property.md">Sensors</a></td>
<td align="left">Gets the list of available sensors.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/UniqueKinectId_Property.md">UniqueKinectId</a></td>
<td align="left">Gets the unique ID for the KinectSensor.</td>
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
<td align="left"><a href="KinectSensor_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Closes and releases system resources associated with the Kinect Sensor.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Methods/GetDefault_Method.md">GetDefault</a></td>
<td align="left">Gets the default sensor.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Methods/Open_Method.md">Open</a></td>
<td align="left">Opens the KinectSensor for use.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Methods/OpenMultiSourceFrameReader.md">OpenMultiSourceFrameReader</a></td>
<td align="left">Creates a frame reader for the multiple frame sources.</td>
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
<td align="left"><a href="KinectSensor_Class/Events/IsAvailableChanged_Event.md">IsAvailableChanged</a></td>
<td align="left">This event fires when the IsAvailable property changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">KinectSensor</a> class changes.</td>
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
TOCTitle : KinectSensor Class
RLTitle : KinectSensor Class
KeywordK : KinectSensor class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.KinectSensor
KeywordF : KinectSensor
KeywordF : WindowsPreview.Kinect.KinectSensor
KeywordA : T:WindowsPreview.Kinect.KinectSensor
AssetID : T:WindowsPreview.Kinect.KinectSensor
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectSensor
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
