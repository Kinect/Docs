AudioBeamSubFrame.AudioBodyCorrelations Property  
================================================  

Acquires the list of the AudioBodyCorrelation objects available in this subframe. <span id="syntaxSection"></span>

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
property IVectorView&lt;<a href="../../AudioBodyCorrelation_Class.md">AudioBodyCorrelation</a>&gt;^ AudioBodyCorrelations {  
         IVectorView&lt;<a href="../../AudioBodyCorrelation_Class.md">AudioBodyCorrelation</a>&gt;^ get ();  
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
<td align="left"><pre><code>public IReadOnlyList&lt;<a href="../../AudioBodyCorrelation_Class.md">AudioBodyCorrelation</a>&gt;AudioBodyCorrelations { get; }</code></pre></td>
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
<td align="left"><pre><code>var audioBodyCorrelations = audioBeamSubFrame.audioBodyCorrelations;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[AudioBodyCorrelation](../../AudioBodyCorrelation_Class.md)\>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[AudioBodyCorrelation](../../AudioBodyCorrelation_Class.md)\>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[AudioBodyCorrelation](../../AudioBodyCorrelation_Class.md)\>

A collection of audio body correlations.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EAB"></span>

See also  
========  

<span id="ID4ECB"></span>
#### Reference  

[AudioBeamSubFrame Class](../../AudioBeamSubFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioBodyCorrelations Property
RLTitle : AudioBeamSubFrame.AudioBodyCorrelations Property
KeywordK : AudioBodyCorrelations property
KeywordK : AudioBeamSubFrame.AudioBodyCorrelations property
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame.AudioBodyCorrelations
KeywordF : AudioBeamSubFrame.AudioBodyCorrelations
KeywordF : AudioBodyCorrelations
KeywordF : WindowsPreview.Kinect.AudioBeamSubFrame.AudioBodyCorrelations
KeywordA : P:WindowsPreview.Kinect.AudioBeamSubFrame.AudioBodyCorrelations
AssetID : P:WindowsPreview.Kinect.AudioBeamSubFrame.AudioBodyCorrelations
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamSubFrame.AudioBodyCorrelations
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
