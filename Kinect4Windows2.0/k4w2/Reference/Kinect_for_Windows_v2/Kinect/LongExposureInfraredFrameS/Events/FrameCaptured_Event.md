LongExposureInfraredFrameSource.FrameCaptured Event  
===================================================  

Event that is raised whenever a frame is captured. <span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../LongExposureInfraredFrameS.md">LongExposureInfraredFrameSource</a>, <a href="../../FrameCapturedEventArgs_Class.md">FrameCapturedEventArgs</a>&gt;^ FrameCaptured {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../LongExposureInfraredFrameS.md">LongExposureInfraredFrameSource</a>, <a href="../../FrameCapturedEventArgs_Class.md">FrameCapturedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../LongExposureInfraredFrameS.md">LongExposureInfraredFrameSource</a>, <a href="../../FrameCapturedEventArgs_Class.md">FrameCapturedEventArgs</a>&gt; FrameCaptured</code></pre></td>
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
<td align="left"><pre><code>function onFrameCaptured(eventArgs) { /* Your code */ }  

// addEventListener syntax  
longExposureInfraredFrameSource.addEventListener(&quot;framecaptured&quot;, onFrameCaptured);  
longExposureInfraredFrameSource.removeEventListener(&quot;framecaptured&quot;, onFrameCaptured);  

- or -  

longExposureInfraredFrameSource.onframecaptured = onFrameCaptured;</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The FrameCaptured event is used to notify the application that the next frame is ready to be delivered to subscribed readers. Applications are only allowed to hold one frame locked at any given time. This event can be used to release the currently locked frame to allow the new one to be delivered to all subscribed readers.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E2"></span>

See also  
========  

<span id="ID4E4"></span>
#### Reference  

[LongExposureInfraredFrameSource Class](../../LongExposureInfraredFrameS.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameCaptured Event
RLTitle : LongExposureInfraredFrameSource.FrameCaptured Event
KeywordK : FrameCaptured event
KeywordK : LongExposureInfraredFrameSource.FrameCaptured event
KeywordF : WindowsPreview.Kinect.LongExposureInfraredFrameSource.FrameCaptured
KeywordF : LongExposureInfraredFrameSource.FrameCaptured
KeywordF : FrameCaptured
KeywordF : WindowsPreview.Kinect.LongExposureInfraredFrameSource.FrameCaptured
KeywordA : E:WindowsPreview.Kinect.LongExposureInfraredFrameSource.FrameCaptured
AssetID : E:WindowsPreview.Kinect.LongExposureInfraredFrameSource.FrameCaptured
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.LongExposureInfraredFrameSource.FrameCaptured
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
