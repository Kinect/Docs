VisualGestureBuilderFrameSource.IsTrackingIdValid Property  
==========================================================  

Gets or sets a value indicating if the tracking ID associated with the frame sourcec is valid. <span id="syntaxSection"></span>

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
property bool IsTrackingIdValid {  
         bool get ();  
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
<td align="left"><pre><code>public bool IsTrackingIdValid { get; }</code></pre></td>
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
<td align="left"><pre><code>var isTrackingIdValid = visualGestureBuilderFrameSource.isTrackingIdValid;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
Type: Boolean  

True if the tracking ID is valid; otherwise false.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="remarks"></span>

Remarks  
=======  

The tracking ID associated with the **VisualGestureBuilderFrameSource** object can become invalid as bodies move in/out of view of the Kinect sensor. Whenever new body frames arrive from the sensor, check to see if any of the body tracking IDs have changed. If a change is detected, update the corresponding VisualGestureBuilderFrameSource object with the latest tracking ID.  

<span id="ID4EEB"></span>

See also  
========  

<span id="ID4EGB"></span>
#### Reference  

[VisualGestureBuilderFrameSource Class](../../VisualGestureBuilderFrameS.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../../Kinect.VisualGestureBuilder.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IsTrackingIdValid Property
RLTitle : VisualGestureBuilderFrameSource.IsTrackingIdValid Property
KeywordK : IsTrackingIdValid property
KeywordK : VisualGestureBuilderFrameSource.IsTrackingIdValid property
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.IsTrackingIdValid
KeywordF : VisualGestureBuilderFrameSource.IsTrackingIdValid
KeywordF : IsTrackingIdValid
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.IsTrackingIdValid
KeywordA : P:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.IsTrackingIdValid
AssetID : P:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.IsTrackingIdValid
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.IsTrackingIdValid
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
