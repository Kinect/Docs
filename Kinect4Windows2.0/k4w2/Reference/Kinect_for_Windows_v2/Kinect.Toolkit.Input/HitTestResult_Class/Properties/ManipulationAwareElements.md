HitTestResult.ManipulationAwareElements Property  
================================================  

Gets or sets the list of [ManipulatableModel](../../ManipulatableModel_Class.md) objects associated with a hit test. <span id="syntaxSection"></span>

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
property IVector&lt;<a href="../../ManipulatableModel_Class.md">ManipulatableModel</a>&gt;^ ManipulationAwareElements {  
         IVector&lt;<a href="../../ManipulatableModel_Class.md">ManipulatableModel</a>&gt;^ get ();  
         void set (IVector&lt;<a href="../../ManipulatableModel_Class.md">ManipulatableModel</a>&gt;^ value);  
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
<td align="left"><pre><code>public IList&lt;<a href="../../ManipulatableModel_Class.md">ManipulatableModel</a>&gt;ManipulationAwareElements { get; set; }</code></pre></td>
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
<td align="left"><pre><code>var manipulationAwareElements = hitTestResult.manipulationAwareElements;  
hitTestResult.manipulationAwareElements = manipulationAwareElements;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EW"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[ManipulatableModel](../../ManipulatableModel_Class.md)\>
Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6.aspx)\<[ManipulatableModel](../../ManipulatableModel_Class.md)\>
Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[ManipulatableModel](../../ManipulatableModel_Class.md)\>

The list of [ManipulatableModel](../../ManipulatableModel_Class.md) objects associated with a hit test.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[HitTestResult Class](../../HitTestResult_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ManipulationAwareElements Property
RLTitle : HitTestResult.ManipulationAwareElements Property
KeywordK : ManipulationAwareElements property
KeywordK : HitTestResult.ManipulationAwareElements property
KeywordF : Microsoft.Kinect.Toolkit.Input.HitTestResult.ManipulationAwareElements
KeywordF : HitTestResult.ManipulationAwareElements
KeywordF : ManipulationAwareElements
KeywordF : Microsoft.Kinect.Toolkit.Input.HitTestResult.ManipulationAwareElements
KeywordA : P:Microsoft.Kinect.Toolkit.Input.HitTestResult.ManipulationAwareElements
AssetID : P:Microsoft.Kinect.Toolkit.Input.HitTestResult.ManipulationAwareElements
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.HitTestResult.ManipulationAwareElements
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
