FrameCapturedEventArgs.RelativeTime Property  
============================================  

Gets the unique relative time at which the frame was captured. <span id="syntaxSection"></span>

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
property TimeSpan RelativeTime {  
         TimeSpan get ();  
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
<td align="left"><pre><code>public TimeSpan RelativeTime { get; }</code></pre></td>
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
<td align="left"><pre><code>var relativeTime = frameCapturedEventArgs.relativeTime;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [TimeSpan](http://msdn.microsoft.com/en-us/library/windows.foundation.timespan.aspx)  
Type: [TimeSpan](http://msdn.microsoft.com/en-us/library/system.timespan.aspx)  
Type: Number  

The timestamp of the captured frame.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[FrameCapturedEventArgs Class](../../FrameCapturedEventArgs_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : RelativeTime Property
RLTitle : FrameCapturedEventArgs.RelativeTime Property
KeywordK : RelativeTime property
KeywordK : FrameCapturedEventArgs.RelativeTime property
KeywordF : WindowsPreview.Kinect.FrameCapturedEventArgs.RelativeTime
KeywordF : FrameCapturedEventArgs.RelativeTime
KeywordF : RelativeTime
KeywordF : WindowsPreview.Kinect.FrameCapturedEventArgs.RelativeTime
KeywordA : P:WindowsPreview.Kinect.FrameCapturedEventArgs.RelativeTime
AssetID : P:WindowsPreview.Kinect.FrameCapturedEventArgs.RelativeTime
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.FrameCapturedEventArgs.RelativeTime
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
