KinectGestureRecognizer.GestureSettings Property  
================================================  

Gets or sets a value that indicates the gesture and manipulation settings supported by an application. <span id="syntaxSection"></span>

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
property <a href="../../KinectGestureSettings.md">KinectGestureSettings</a> GestureSettings {  
         <a href="../../KinectGestureSettings.md">KinectGestureSettings</a> get ();  
         void set (<a href="../../KinectGestureSettings.md">KinectGestureSettings</a> value);  
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
<td align="left"><pre><code>public <a href="../../KinectGestureSettings.md">KinectGestureSettings</a> GestureSettings { get; set; }</code></pre></td>
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
<td align="left"><pre><code>var gestureSettings = kinectGestureRecognizer.gestureSettings;  
kinectGestureRecognizer.gestureSettings = gestureSettings;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ES"></span>
#### Property value  

Type: [KinectGestureSettings](../../KinectGestureSettings.md)  
 The gesture settings supported by an application. The value of this property is a bitwise OR of members of **GestureSettings** enumeration.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GestureSettings Property
RLTitle : KinectGestureRecognizer.GestureSettings Property
KeywordK : GestureSettings property
KeywordK : KinectGestureRecognizer.GestureSettings property
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.GestureSettings
KeywordF : KinectGestureRecognizer.GestureSettings
KeywordF : GestureSettings
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.GestureSettings
KeywordA : P:WindowsPreview.Kinect.Input.KinectGestureRecognizer.GestureSettings
AssetID : P:WindowsPreview.Kinect.Input.KinectGestureRecognizer.GestureSettings
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.GestureSettings
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
