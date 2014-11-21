KinectGestureRecognizer.AutoProcessInertia Property  
===================================================  

Gets or sets a value that indicates whether manipulations during inertia are generated automatically. If false, the app is expected to call ProcessInertia periodically. <span id="syntaxSection"></span>

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
property bool AutoProcessInertia {  
         bool get ();  
         void set (bool value);  
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
<td align="left"><pre><code>public bool AutoProcessInertia { get; set; }</code></pre></td>
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
<td align="left"><pre><code>var autoProcessInertia = kinectGestureRecognizer.autoProcessInertia;  
kinectGestureRecognizer.autoProcessInertia = autoProcessInertia;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ES"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
Type: Boolean  

True if manipulations are generated automatically; otherwise false. The default value is true.  

<span id="remarks"></span>

Remarks  
=======  

If the value for **AutoProcessInertia** is set to false, applications must call [ProcessInertia](../Methods/ProcessInertia_Method.md) to handle events during inertia.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[KinectGestureRecognizer Class](../../KinectGestureRecognizer.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AutoProcessInertia Property
RLTitle : KinectGestureRecognizer.AutoProcessInertia Property
KeywordK : AutoProcessInertia property
KeywordK : KinectGestureRecognizer.AutoProcessInertia property
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.AutoProcessInertia
KeywordF : KinectGestureRecognizer.AutoProcessInertia
KeywordF : AutoProcessInertia
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.AutoProcessInertia
KeywordA : P:WindowsPreview.Kinect.Input.KinectGestureRecognizer.AutoProcessInertia
AssetID : P:WindowsPreview.Kinect.Input.KinectGestureRecognizer.AutoProcessInertia
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.AutoProcessInertia
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
