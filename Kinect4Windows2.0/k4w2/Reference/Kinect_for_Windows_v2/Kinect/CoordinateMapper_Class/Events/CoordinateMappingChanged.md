CoordinateMapper.CoordinateMappingChanged Event  
===============================================  

Event that is raised when any of the mappings between camera, color, and depth space change. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
event TypedEventHandler&lt;<a href="../../CoordinateMapper_Class.md">CoordinateMapper</a>, <a href="../../CoordinateMappingChangedEv.md">CoordinateMappingChangedEventArgs</a>&gt;^ CoordinateMappingChanged {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../CoordinateMapper_Class.md">CoordinateMapper</a>, <a href="../../CoordinateMappingChangedEv.md">CoordinateMappingChangedEventArgs</a>&gt;^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../CoordinateMapper_Class.md">CoordinateMapper</a>, <a href="../../CoordinateMappingChangedEv.md">CoordinateMappingChangedEventArgs</a>&gt; CoordinateMappingChanged</code></pre></td>
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
<td align="left"><pre><code>function onCoordinateMappingChanged(eventArgs) { /* Your code */ }  

// addEventListener syntax  
coordinateMapper.addEventListener(&quot;coordinatemappingchanged&quot;, onCoordinateMappingChanged);  
coordinateMapper.removeEventListener(&quot;coordinatemappingchanged&quot;, onCoordinateMappingChanged);  

- or -  

coordinateMapper.oncoordinatemappingchanged = onCoordinateMappingChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[CoordinateMapper Class](../../CoordinateMapper_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CoordinateMappingChanged Event
RLTitle : CoordinateMapper.CoordinateMappingChanged Event
KeywordK : CoordinateMappingChanged event
KeywordK : CoordinateMapper.CoordinateMappingChanged event
KeywordF : WindowsPreview.Kinect.CoordinateMapper.CoordinateMappingChanged
KeywordF : CoordinateMapper.CoordinateMappingChanged
KeywordF : CoordinateMappingChanged
KeywordF : WindowsPreview.Kinect.CoordinateMapper.CoordinateMappingChanged
KeywordA : E:WindowsPreview.Kinect.CoordinateMapper.CoordinateMappingChanged
AssetID : E:WindowsPreview.Kinect.CoordinateMapper.CoordinateMappingChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CoordinateMapper.CoordinateMappingChanged
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
