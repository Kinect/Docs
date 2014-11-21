BodyIndexFrameReader.PropertyChanged Event  
==========================================  

Occurs when a property of the [BodyIndexFrameReader](../../BodyIndexFrameReader_Class.md) class changes. <span id="syntaxSection"></span>

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
event <a href="../../../Data/PropertyChangedEventHandler.md">PropertyChangedEventHandler</a>^ PropertyChanged {  
         EventRegistrationToken add (<a href="../../../Data/PropertyChangedEventHandler.md">PropertyChangedEventHandler</a>^ value);  
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
<td align="left"><pre><code>public event <a href="../../../Data/PropertyChangedEventHandler.md">PropertyChangedEventHandler</a> PropertyChanged</code></pre></td>
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
bodyIndexFrameReader.addEventListener(&quot;propertychanged&quot;, onPropertyChanged);  
bodyIndexFrameReader.removeEventListener(&quot;propertychanged&quot;, onPropertyChanged);  

- or -  

bodyIndexFrameReader.onpropertychanged = onPropertyChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EU"></span>

See also  
========  

<span id="ID4EW"></span>
#### Reference  

[BodyIndexFrameReader Class](../../BodyIndexFrameReader_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PropertyChanged Event
RLTitle : BodyIndexFrameReader.PropertyChanged Event
KeywordK : PropertyChanged event
KeywordK : BodyIndexFrameReader.PropertyChanged event
KeywordF : WindowsPreview.Kinect.BodyIndexFrameReader.PropertyChanged
KeywordF : BodyIndexFrameReader.PropertyChanged
KeywordF : PropertyChanged
KeywordF : WindowsPreview.Kinect.BodyIndexFrameReader.PropertyChanged
KeywordA : E:WindowsPreview.Kinect.BodyIndexFrameReader.PropertyChanged
AssetID : E:WindowsPreview.Kinect.BodyIndexFrameReader.PropertyChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyIndexFrameReader.PropertyChanged
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
