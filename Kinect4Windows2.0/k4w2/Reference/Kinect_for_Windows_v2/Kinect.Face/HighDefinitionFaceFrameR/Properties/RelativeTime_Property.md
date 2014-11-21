HighDefinitionFaceFrameReference.RelativeTime Property  
======================================================  

Gets the relative time of this frame. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>var relativeTime = highDefinitionFaceFrameReference.relativeTime;</code></pre></td>
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

The relative time of this frame.  

<span id="remarks"></span>

Remarks  
=======  

Relative times for frames can be compared against one another in real time to determine the order in which the frames were produced. However, there is no guaranteed epoch for all frames from all game play sessions. For example, if you were to compare the relative time of a frame from a game played a week ago to a frame from a game played today, the frame from the game played today could possibly appear as if it was created earlier than the one from a week ago.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[HighDefinitionFaceFrameReference Class](../../HighDefinitionFaceFrameR.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : RelativeTime Property
RLTitle : HighDefinitionFaceFrameReference.RelativeTime Property
KeywordK : RelativeTime property
KeywordK : HighDefinitionFaceFrameReference.RelativeTime property
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.RelativeTime
KeywordF : HighDefinitionFaceFrameReference.RelativeTime
KeywordF : RelativeTime
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.RelativeTime
KeywordA : P:Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.RelativeTime
AssetID : P:Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.RelativeTime
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameReference.RelativeTime
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
