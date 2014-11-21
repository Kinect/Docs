HighDefinitionFaceFrameReader Class  
===================================  

Represents a high-definition face frame reader. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class HighDefinitionFaceFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class HighDefinitionFaceFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var highDefinitionFaceFrameReader = Microsoft.Kinect.Face.HighDefinitionFaceFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**HighDefinitionFaceFrameReader** has the following members.  

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
<td align="left"><a href="HighDefinitionFaceFrameRea/Properties/HighDefinitionFaceFrameSou.md">HighDefinitionFaceFrameSource</a></td>
<td align="left">Gets the high-definition face frame source.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameRea/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">Gets or sets a boolean that indicates if the reader is paused.</td>
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
<td align="left"><a href="HighDefinitionFaceFrameRea/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">&gt;Gets the most recent frame. It may return null if no frame is available.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameRea/Methods/Close_Method.md">Close</a></td>
<td align="left">Closes the HighDefinitionFrameReader.</td>
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
<td align="left"><a href="HighDefinitionFaceFrameRea/Events/FrameArrived_Event.md">FrameArrived</a></td>
<td align="left">Occurs when a new frame is ready.</td>
</tr>
<tr class="even">
<td align="left"><a href="HighDefinitionFaceFrameRea/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left">Occurs when a property of the <a href="">HighDefinitionFaceFrameReader</a> changes.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E4"></span>

See also  
========  

<span id="ID4E6"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HighDefinitionFaceFrameReader Class
RLTitle : HighDefinitionFaceFrameReader Class
KeywordK : HighDefinitionFaceFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader
KeywordF : HighDefinitionFaceFrameReader
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader
KeywordA : T:Microsoft.Kinect.Face.HighDefinitionFaceFrameReader
AssetID : T:Microsoft.Kinect.Face.HighDefinitionFaceFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader
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
