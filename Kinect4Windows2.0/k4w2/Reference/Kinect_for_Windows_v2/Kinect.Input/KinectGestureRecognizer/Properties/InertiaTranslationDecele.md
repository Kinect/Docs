KinectGestureRecognizer.InertiaTranslationDeceleration Property  
===============================================================  

Gets or sets a value that indicates the rate of deceleration from the start of inertia to the end of inertia (when the translation manipulation is complete). <span id="syntaxSection"></span>

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
property float32 InertiaTranslationDeceleration {  
         float32 get ();  
         void set (float32 value);  
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
<td align="left"><pre><code>public float InertiaTranslationDeceleration { get; set; }</code></pre></td>
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
<td align="left"><pre><code>var inertiaTranslationDeceleration = kinectGestureRecognizer.inertiaTranslationDeceleration;  
kinectGestureRecognizer.inertiaTranslationDeceleration = inertiaTranslationDeceleration;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ES"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: float32  
Type: [float](http://msdn.microsoft.com/en-us/library/system.single.aspx)  
Type: Number  

The rate of deceleration, in DIPs/ms<sup>2</sup>.  

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
TOCTitle : InertiaTranslationDeceleration Property
RLTitle : KinectGestureRecognizer.InertiaTranslationDeceleration Property
KeywordK : InertiaTranslationDeceleration property
KeywordK : KinectGestureRecognizer.InertiaTranslationDeceleration property
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.InertiaTranslationDeceleration
KeywordF : KinectGestureRecognizer.InertiaTranslationDeceleration
KeywordF : InertiaTranslationDeceleration
KeywordF : WindowsPreview.Kinect.Input.KinectGestureRecognizer.InertiaTranslationDeceleration
KeywordA : P:WindowsPreview.Kinect.Input.KinectGestureRecognizer.InertiaTranslationDeceleration
AssetID : P:WindowsPreview.Kinect.Input.KinectGestureRecognizer.InertiaTranslationDeceleration
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectGestureRecognizer.InertiaTranslationDeceleration
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
