PropertyChangedEventHandler Delegate  
====================================  

Represents the method that will handle the PropertyChanged event raised when a property is changed on a component. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public delegate void PropertyChangedEventHandler(  
         Object^ sender,  
         <a href="PropertyChangedEventArgs.md">PropertyChangedEventArgs</a>^ e  
)</code></pre></td>
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
<td align="left"><pre><code>public delegate void PropertyChangedEventHandler (  
         Objectsender,  
         <a href="PropertyChangedEventArgs.md">PropertyChangedEventArgs</a>e  
)</code></pre></td>
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
<td align="left"><pre><code>var propertyChangedEventHandler = function (sender, e) {  
        /* Your code */  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sender*    
[C++] Type: [Object](http://msdn.microsoft.com/en-us/library/hh748265.aspx)  
  [C\#] Type: [Object](http://msdn.microsoft.com/en-us/library/system.object.aspx)  
  [JavaScript] Type: Object  
   

The source of the event.  

*e*    
Type: [PropertyChangedEventArgs](PropertyChangedEventArgs.md)  
A [PropertyChangedEventArgs](PropertyChangedEventArgs.md) that contains the event data.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Data  
**Metadata:**windowspreview.data.winmd  

<span id="ID4EFB"></span>

See also  
========  

<span id="ID4EHB"></span>
#### Reference  

[WindowsPreview.Data Namespace](../Data.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : PropertyChangedEventHandler Delegate
RLTitle : PropertyChangedEventHandler Delegate
KeywordK : PropertyChangedEventHandler delegate
KeywordK : WindowsPreview.Data.PropertyChangedEventHandler delegate
HelpPriority : 2
KeywordF : WindowsPreview.Data.PropertyChangedEventHandler
KeywordF : PropertyChangedEventHandler
KeywordF : WindowsPreview.Data.PropertyChangedEventHandler
KeywordA : T:WindowsPreview.Data.PropertyChangedEventHandler
AssetID : T:WindowsPreview.Data.PropertyChangedEventHandler
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.data.winmd
APIName : WindowsPreview.Data.PropertyChangedEventHandler
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
