CursorModel.ClampedPressExtent Property  
=======================================  

Gets the extent of a clamped press gesture. <span id="syntaxSection"></span>

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
property float32 ClampedPressExtent {  
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
<td align="left"><pre><code>public float ClampedPressExtent { get; }</code></pre></td>
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
<td align="left"><pre><code>var clampedPressExtent = cursorModel.clampedPressExtent;</code></pre></td>
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

Gets the current PressExtent value, which represents the progress toward "press down". This is a floating point value between 0 and 1 where 1 indicates fully pressed.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[CursorModel Class](../../CursorModel_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ClampedPressExtent Property
RLTitle : CursorModel.ClampedPressExtent Property
KeywordK : ClampedPressExtent property
KeywordK : CursorModel.ClampedPressExtent property
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorModel.ClampedPressExtent
KeywordF : CursorModel.ClampedPressExtent
KeywordF : ClampedPressExtent
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorModel.ClampedPressExtent
KeywordA : P:Microsoft.Kinect.Toolkit.Input.CursorModel.ClampedPressExtent
AssetID : P:Microsoft.Kinect.Toolkit.Input.CursorModel.ClampedPressExtent
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.CursorModel.ClampedPressExtent
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
