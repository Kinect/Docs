KinectPointerPoint.Position Property  
====================================  

Gets the location of the pointer input in client coordinates. <span id="syntaxSection"></span>

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
property Point Position {  
         Point get ();  
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
<td align="left"><pre><code>public Point Position { get; }</code></pre></td>
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
<td align="left"><pre><code>var position = kinectPointerPoint.position;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The client coordinates, in device-independent pixels (DIPs).  

<span id="remarks"></span>

Remarks  
=======  

**Position** contains the client coordinates of the pointer input as interpreted by the system. Under some circumstances, such as input prediction, this data can be modified by the system to compensate for hardware latency or message latency due to inherent delays in sensing and processing the pointer location on the digitizer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EEB"></span>

See also  
========  

<span id="ID4EGB"></span>
#### Reference  

[KinectPointerPoint Class](../../KinectPointerPoint_Class.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Position Property
RLTitle : KinectPointerPoint.Position Property
KeywordK : Position property
KeywordK : KinectPointerPoint.Position property
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPoint.Position
KeywordF : KinectPointerPoint.Position
KeywordF : Position
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPoint.Position
KeywordA : P:WindowsPreview.Kinect.Input.KinectPointerPoint.Position
AssetID : P:WindowsPreview.Kinect.Input.KinectPointerPoint.Position
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPointerPoint.Position
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
