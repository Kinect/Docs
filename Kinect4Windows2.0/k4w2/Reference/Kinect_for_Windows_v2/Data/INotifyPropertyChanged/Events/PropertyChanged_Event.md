INotifyPropertyChanged.PropertyChanged Event  
============================================  

Occurs when a property value changes.<span id="syntaxSection"></span>

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
event <a href="../../PropertyChangedEventHandler.md">PropertyChangedEventHandler</a>^ PropertyChanged {  
         EventRegistrationToken add (<a href="../../PropertyChangedEventHandler.md">PropertyChangedEventHandler</a>^ value);  
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
<td align="left"><pre><code>public event <a href="../../PropertyChangedEventHandler.md">PropertyChangedEventHandler</a> PropertyChanged</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Data  
**Metadata:**windowspreview.data.winmd  

<span id="ID4EV"></span>

See also  
========  

<span id="ID4EX"></span>
#### Reference  

[INotifyPropertyChanged Interface](../../INotifyPropertyChanged.md)  
 [WindowsPreview.Data Namespace](../../../Data.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PropertyChanged Event
RLTitle : INotifyPropertyChanged.PropertyChanged Event
KeywordK : PropertyChanged event
KeywordK : INotifyPropertyChanged.PropertyChanged event
KeywordF : WindowsPreview.Data.INotifyPropertyChanged.PropertyChanged
KeywordF : INotifyPropertyChanged.PropertyChanged
KeywordF : PropertyChanged
KeywordF : WindowsPreview.Data.INotifyPropertyChanged.PropertyChanged
KeywordA : E:WindowsPreview.Data.INotifyPropertyChanged.PropertyChanged
AssetID : E:WindowsPreview.Data.INotifyPropertyChanged.PropertyChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.data.winmd
APIName : WindowsPreview.Data.INotifyPropertyChanged.PropertyChanged
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
