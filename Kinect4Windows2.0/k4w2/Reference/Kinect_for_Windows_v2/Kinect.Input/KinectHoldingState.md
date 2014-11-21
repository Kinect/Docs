KinectHoldingState Enumeration  
==============================  

Specifies the state of the [Holding](KinectGestureRecognizer/Events/Holding_Event.md) event. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public enum class KinectHoldingState</code></pre></td>
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
<td align="left"><pre><code>public enum KinectHoldingState</code></pre></td>
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
<td align="left"><pre><code>var kinectHoldingState = WindowsPreview.Kinect.Input.KinectHoldingState.canceled;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EEB"></span>

Members  
=======  

| Member        | Value | Description                                                                                                                                                                                  |
|---------------|-------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Canceled**  | 2     | An additional contact is detected, a subsequent gesture (such as a slide) is detected, or the [CompleteGesture](KinectGestureRecognizer/Methods/CompleteGesture_Method.md) method is called. |
| **Completed** | 1     | The single contact is lifted.                                                                                                                                                                |
| **Started**   | 0     | A single contact has been detected and a time threshold is crossed without the contact being lifted, another contact detected, or another gesture started.                                   |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ELB"></span>

See also  
========  

<span id="ID4ENB"></span>
#### Reference  

[WindowsPreview.Kinect.Input Namespace](../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectHoldingState Enumeration
RLTitle : KinectHoldingState Enumeration
KeywordK : KinectHoldingState enumeration
KeywordK : WindowsPreview.Kinect.Input.KinectHoldingState enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.Input.KinectHoldingState
KeywordF : KinectHoldingState
KeywordF : WindowsPreview.Kinect.Input.KinectHoldingState
KeywordA : T:WindowsPreview.Kinect.Input.KinectHoldingState
AssetID : T:WindowsPreview.Kinect.Input.KinectHoldingState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectHoldingState
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
