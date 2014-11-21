HighDefinitionFaceFrameReader.PropertyChanged Event  
===================================================  

Occurs when a property of the [HighDefinitionFaceFrameReader](../../HighDefinitionFaceFrameRea.md) changes. <span id="syntaxSection"></span>

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
highDefinitionFaceFrameReader.addEventListener(&quot;propertychanged&quot;, onPropertyChanged);  
highDefinitionFaceFrameReader.removeEventListener(&quot;propertychanged&quot;, onPropertyChanged);  

- or -  

highDefinitionFaceFrameReader.onpropertychanged = onPropertyChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EU"></span>

See also  
========  

<span id="ID4EW"></span>
#### Reference  

[HighDefinitionFaceFrameReader Class](../../HighDefinitionFaceFrameRea.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PropertyChanged Event
RLTitle : HighDefinitionFaceFrameReader.PropertyChanged Event
KeywordK : PropertyChanged event
KeywordK : HighDefinitionFaceFrameReader.PropertyChanged event
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.PropertyChanged
KeywordF : HighDefinitionFaceFrameReader.PropertyChanged
KeywordF : PropertyChanged
KeywordF : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.PropertyChanged
KeywordA : E:Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.PropertyChanged
AssetID : E:Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.PropertyChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.HighDefinitionFaceFrameReader.PropertyChanged
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
