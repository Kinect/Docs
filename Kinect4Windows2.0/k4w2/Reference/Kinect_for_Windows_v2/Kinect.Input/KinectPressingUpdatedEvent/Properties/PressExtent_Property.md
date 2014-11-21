KinectPressingUpdatedEventArgs.PressExtent Property  
===================================================  

Gets a normalized Z value for the pressing gesture. <span id="syntaxSection"></span>

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
property float32 PressExtent {  
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
<td align="left"><pre><code>public float PressExtent { get; }</code></pre></td>
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
<td align="left"><pre><code>var pressExtent = kinectPressingUpdatedEventArgs.pressExtent;</code></pre></td>
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

A normalized Z value for the pressing gesture.  

<span id="remarks"></span>

Remarks  
=======  

The value of this property is 0.0 when a pressing gesture starts. As the user presses forward, the value increases until it reaches 1.0, which indicates the tappable gesture recognizer has been pressed. The value decreases as the user moves the pointer backwards, although it will not go negative. The value is reset to 0.0 when a pressing gesture on another tappable gesture recognizer begins.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[KinectPressingUpdatedEventArgs Class](../../KinectPressingUpdatedEvent.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PressExtent Property
RLTitle : KinectPressingUpdatedEventArgs.PressExtent Property
KeywordK : PressExtent property
KeywordK : KinectPressingUpdatedEventArgs.PressExtent property
KeywordF : WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.PressExtent
KeywordF : KinectPressingUpdatedEventArgs.PressExtent
KeywordF : PressExtent
KeywordF : WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.PressExtent
KeywordA : P:WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.PressExtent
AssetID : P:WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.PressExtent
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.PressExtent
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
