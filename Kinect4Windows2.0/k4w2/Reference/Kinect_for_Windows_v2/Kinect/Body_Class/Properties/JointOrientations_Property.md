Body.JointOrientations Property  
===============================  

Gets the joint orientations of the body. <span id="syntaxSection"></span>

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
property IMapView&lt;<a href="../../JointType_Enumeration.md">JointType</a>, <a href="../../JointOrientation_Structure.md">JointOrientation</a>&gt;^ JointOrientations {  
         IMapView&lt;<a href="../../JointType_Enumeration.md">JointType</a>, <a href="../../JointOrientation_Structure.md">JointOrientation</a>&gt;^ get ();  
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
<td align="left"><pre><code>public IReadOnlyDictionary&lt;<a href="../../JointType_Enumeration.md">JointType</a>, <a href="../../JointOrientation_Structure.md">JointOrientation</a>&gt;JointOrientations { get; }</code></pre></td>
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
<td align="left"><pre><code>var jointOrientations = body.jointOrientations;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EU"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IMapView](http://msdn.microsoft.com/en-us/library/br226037.aspx)\<[JointType](../../JointType_Enumeration.md), [JointOrientation](../../JointOrientation_Structure.md)\>
Type: [IReadOnlyDictionary](http://msdn.microsoft.com/en-us/library/hh136548.aspx)\<[JointType](../../JointType_Enumeration.md), [JointOrientation](../../JointOrientation_Structure.md)\>
Type: [IMapView](http://msdn.microsoft.com/en-us/library/br226037.aspx)\<[JointType](../../JointType_Enumeration.md), [JointOrientation](../../JointOrientation_Structure.md)\>

The joint orientations of the body.  

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
TOCTitle : JointOrientations Property
RLTitle : Body.JointOrientations Property
KeywordK : JointOrientations property
KeywordK : Body.JointOrientations property
KeywordF : WindowsPreview.Kinect.Body.JointOrientations
KeywordF : Body.JointOrientations
KeywordF : JointOrientations
KeywordF : WindowsPreview.Kinect.Body.JointOrientations
KeywordA : P:WindowsPreview.Kinect.Body.JointOrientations
AssetID : P:WindowsPreview.Kinect.Body.JointOrientations
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Body.JointOrientations
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
