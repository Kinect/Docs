VisualGestureBuilderFrameSource.TrackingIdLost Event  
====================================================  

Occurs when the tracking ID of the Visual Gesture Builder frame source is lost.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../VisualGestureBuilderFram.md">VisualGestureBuilderFrameSource</a>, <a href="../../TrackingIdLostEventArgs.md">TrackingIdLostEventArgs</a>&gt;^ TrackingIdLost {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../VisualGestureBuilderFram.md">VisualGestureBuilderFrameSource</a>, <a href="../../TrackingIdLostEventArgs.md">TrackingIdLostEventArgs</a>&gt;^ value);  
         void remove (EventRegistrationToken token);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../VisualGestureBuilderFram.md">VisualGestureBuilderFrameSource</a>, <a href="../../TrackingIdLostEventArgs.md">TrackingIdLostEventArgs</a>&gt; TrackingIdLost</code></pre></td>
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
<td align="left"><pre><code>function onTrackingIdLost(eventArgs) { /* Your code */ }  

// addEventListener syntax  
visualGestureBuilderFrameSource.addEventListener(&quot;trackingidlost&quot;, onTrackingIdLost);  
visualGestureBuilderFrameSource.removeEventListener(&quot;trackingidlost&quot;, onTrackingIdLost);  

- or -  

visualGestureBuilderFrameSource.ontrackingidlost = onTrackingIdLost;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[VisualGestureBuilderFrameSource Class](../../VisualGestureBuilderFram.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../../Kinect.VisualGestureBuil.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TrackingIdLost Event
RLTitle : VisualGestureBuilderFrameSource.TrackingIdLost Event
KeywordK : TrackingIdLost event
KeywordK : VisualGestureBuilderFrameSource.TrackingIdLost event
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingIdLost
KeywordF : VisualGestureBuilderFrameSource.TrackingIdLost
KeywordF : TrackingIdLost
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingIdLost
KeywordA : E:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingIdLost
AssetID : E:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingIdLost
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.TrackingIdLost
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
