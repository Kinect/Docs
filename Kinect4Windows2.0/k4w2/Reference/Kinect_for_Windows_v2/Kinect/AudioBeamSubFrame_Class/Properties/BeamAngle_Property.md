AudioBeamSubFrame.BeamAngle Property  
====================================  

Gets the angle (in radians) of the audio beam, which is the direction that the sensor is actively listening. <span id="syntaxSection"></span>

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
property float32 BeamAngle {  
         float32 get ();  
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
<td align="left"><pre><code>public float BeamAngle { get; }</code></pre></td>
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
<td align="left"><pre><code>var beamAngle = audioBeamSubFrame.beamAngle;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: float32  
Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
Type: Number  

The beam angle.  

<span id="remarks"></span>

Remarks  
=======  

This is a value in radians between -0.872665 to +0.872665 (-50 and +50 in degrees) in .087 (5 degree) increments.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EBB"></span>

See also  
========  

<span id="ID4EDB"></span>
#### Reference  

[AudioBeamSubFrame Class](../../AudioBeamSubFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : BeamAngle Property
RLTitle : AudioBeamSubFrame.BeamAngle Property
KeywordK : BeamAngle property
KeywordK : AudioBeamSubFrame.BeamAngle property
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame.BeamAngle
KeywordF : AudioBeamSubFrame.BeamAngle
KeywordF : BeamAngle
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame.BeamAngle
KeywordA : P:WindowsPreview.Kinect.AudioBeamSubFrame.BeamAngle
AssetID : P:WindowsPreview.Kinect.AudioBeamSubFrame.BeamAngle
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamSubFrame.BeamAngle
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
