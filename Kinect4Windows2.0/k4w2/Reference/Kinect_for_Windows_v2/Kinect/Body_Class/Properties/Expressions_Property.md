Body.Expressions Property  
=========================  

Gets the status of the body's possible expressions. This API is not implemented in the Kinect for Windows v2 SDK and will always return null. It is included to support cross-compilation with the Xbox SDK. <span id="syntaxSection"></span>

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
property IMapView&lt;<a href="../../Expression_Enumeration.md">Expression</a>, <a href="../../DetectionResult_Enumeration.md">DetectionResult</a>&gt;^ Expressions {  
         IMapView&lt;<a href="../../Expression_Enumeration.md">Expression</a>, <a href="../../DetectionResult_Enumeration.md">DetectionResult</a>&gt;^ get ();  
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
<td align="left"><pre><code>public IReadOnlyDictionary&lt;<a href="../../Expression_Enumeration.md">Expression</a>, <a href="../../DetectionResult_Enumeration.md">DetectionResult</a>&gt;Expressions { get; }</code></pre></td>
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
<td align="left"><pre><code>var expressions = body.expressions;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EU"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IMapView](http://msdn.microsoft.com/en-us/library/br226037.aspx)\<[Expression](../../Expression_Enumeration.md), [DetectionResult](../../DetectionResult_Enumeration.md)\>
Type: [IReadOnlyDictionary](http://msdn.microsoft.com/en-us/library/hh136548.aspx)\<[Expression](../../Expression_Enumeration.md), [DetectionResult](../../DetectionResult_Enumeration.md)\>
Type: [IMapView](http://msdn.microsoft.com/en-us/library/br226037.aspx)\<[Expression](../../Expression_Enumeration.md), [DetectionResult](../../DetectionResult_Enumeration.md)\>

Returns null.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[Body Class](../../Body_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Expressions Property
RLTitle : Body.Expressions Property
KeywordK : Expressions property
KeywordK : Body.Expressions property
KeywordF : WindowsPreview.Kinect.Body.Expressions
KeywordF : Body.Expressions
KeywordF : Expressions
KeywordF : WindowsPreview.Kinect.Body.Expressions
KeywordA : P:WindowsPreview.Kinect.Body.Expressions
AssetID : P:WindowsPreview.Kinect.Body.Expressions
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Body.Expressions
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
