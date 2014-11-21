KinectPressingUpdatedEventArgs.Position Property  
================================================  

Gets the location of the pointer associated with the manipulation for the last [PressingUpdated](../../KinectGestureRecognizer/Events/PressingUpdated_Event.md) event. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>var position = kinectPressingUpdatedEventArgs.position;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EV"></span>
#### Property value  

Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The screen coordinates, in device-independent pixels (DIPs).  

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

[KinectPressingUpdatedEventArgs Class](../../KinectPressingUpdatedEvent.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Position Property
RLTitle : KinectPressingUpdatedEventArgs.Position Property
KeywordK : Position property
KeywordK : KinectPressingUpdatedEventArgs.Position property
KeywordF : WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.Position
KeywordF : KinectPressingUpdatedEventArgs.Position
KeywordF : Position
KeywordF : WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.Position
KeywordA : P:WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.Position
AssetID : P:WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.Position
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPressingUpdatedEventArgs.Position
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
