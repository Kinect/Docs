VisualGestureBuilderFrameSource.PropertyChanged Event  
=====================================================  

Occurs when a property of the [VisualGestureBuilderFrameSource](../../VisualGestureBuilderFram.md) changes. <span id="syntaxSection"></span>

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
event <a href="../../../Data/PropertyChangedEventHand.md">PropertyChangedEventHandler</a>^ PropertyChanged {  
         EventRegistrationToken add (<a href="../../../Data/PropertyChangedEventHand.md">PropertyChangedEventHandler</a>^ value);  
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
<td align="left"><pre><code>public event <a href="../../../Data/PropertyChangedEventHand.md">PropertyChangedEventHandler</a> PropertyChanged</code></pre></td>
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
<td align="left"><pre><code>function onPropertyChanged(eventArgs) { /* Your code */ }  

// addEventListener syntax  
visualGestureBuilderFrameSource.addEventListener(&quot;propertychanged&quot;, onPropertyChanged);  
visualGestureBuilderFrameSource.removeEventListener(&quot;propertychanged&quot;, onPropertyChanged);  

- or -  

visualGestureBuilderFrameSource.onpropertychanged = onPropertyChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4EU"></span>

See also  
========  

<span id="ID4EW"></span>
#### Reference  

[VisualGestureBuilderFrameSource Class](../../VisualGestureBuilderFram.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../../Kinect.VisualGestureBuil.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PropertyChanged Event
RLTitle : VisualGestureBuilderFrameSource.PropertyChanged Event
KeywordK : PropertyChanged event
KeywordK : VisualGestureBuilderFrameSource.PropertyChanged event
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.PropertyChanged
KeywordF : VisualGestureBuilderFrameSource.PropertyChanged
KeywordF : PropertyChanged
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.PropertyChanged
KeywordA : E:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.PropertyChanged
AssetID : E:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.PropertyChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.PropertyChanged
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
