KinectPointerPoint.RawPosition Property  
=======================================  

Gets the client coordinates of the pointer point. <span id="syntaxSection"></span>

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
property Point RawPosition {  
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
<td align="left"><pre><code>public Point RawPosition { get; }</code></pre></td>
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
<td align="left"><pre><code>var rawPosition = kinectPointerPoint.rawPosition;</code></pre></td>
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

**RawPosition** contains the client coordinates of the input pointer as reported by the input device. Under some circumstances, such as input prediction, this data can be modified by the system to compensate for hardware latency or message latency due to inherent delays in sensing and processing the pointer location on the digitizer.  

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
TOCTitle : RawPosition Property
RLTitle : KinectPointerPoint.RawPosition Property
KeywordK : RawPosition property
KeywordK : KinectPointerPoint.RawPosition property
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPoint.RawPosition
KeywordF : KinectPointerPoint.RawPosition
KeywordF : RawPosition
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPoint.RawPosition
KeywordA : P:WindowsPreview.Kinect.Input.KinectPointerPoint.RawPosition
AssetID : P:WindowsPreview.Kinect.Input.KinectPointerPoint.RawPosition
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPointerPoint.RawPosition
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
