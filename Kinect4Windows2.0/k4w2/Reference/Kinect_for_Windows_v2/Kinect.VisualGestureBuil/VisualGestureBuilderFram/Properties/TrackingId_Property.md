VisualGestureBuilderFrameSource.TrackingId Property  
===================================================  

Gets or sets the tracking ID associated with the gesture frame source. <span id="syntaxSection"></span>

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
property uint64 TrackingId {  
         uint64 get ();  
         void set (uint64 value);  
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
<td align="left"><pre><code>public ulong TrackingId { get; set; }</code></pre></td>
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
<td align="left"><pre><code>var trackingId = visualGestureBuilderFrameSource.trackingId;  
visualGestureBuilderFrameSource.trackingId = trackingId;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ES"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: uint64  
Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
Type: Number  

The tracking ID.  

<span id="remarks"></span>

Remarks  
=======  

The tracking ID associated with the [VisualGestureBuilderFrameSource](../../VisualGestureBuilderFram.md) object can become invalid as bodies move in/out of view of the Kinect sensor. Whenever new body frames arrive from the sensor, check to see if any of the body tracking IDs have changed. If a change is detected, update the corresponding [VisualGestureBuilderFrameSource](../../VisualGestureBuilderFram.md) object with the latest tracking ID.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[VisualGestureBuilderFrameSource Class](../../VisualGestureBuilderFram.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../../Kinect.VisualGestureBuil.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TrackingId Property
RLTitle : VisualGestureBuilderFrameSource.TrackingId Property
KeywordK : TrackingId property
KeywordK : VisualGestureBuilderFrameSource.TrackingId property
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingId
KeywordF : VisualGestureBuilderFrameSource.TrackingId
KeywordF : TrackingId
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingId
KeywordA : P:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingId
AssetID : P:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingId
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingId
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
