FaceModel.TriangleIndices Property  
==================================  

Gets the collection of triangle indices for the face model. <span id="syntaxSection"></span>

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
static property IVectorView&lt;uint32, &gt;^ TriangleIndices {  
         IVectorView&lt;uint32, &gt;^ get ();  
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
<td align="left"><pre><code>public static IReadOnlyList&lt;uint, &gt;TriangleIndices { get; }</code></pre></td>
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
<td align="left"><pre><code>var triangleIndices = Microsoft.Kinect.Face.FaceModel.triangleIndices;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ES"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<uint32, \>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx), \>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<Number, \>

A collection of triangle indices.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[FaceModel Class](../../FaceModel_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TriangleIndices Property
RLTitle : FaceModel.TriangleIndices Property
KeywordK : TriangleIndices property
KeywordK : FaceModel.TriangleIndices property
KeywordF : Microsoft.Kinect.Face.FaceModel.TriangleIndices
KeywordF : FaceModel.TriangleIndices
KeywordF : TriangleIndices
KeywordF : Microsoft.Kinect.Face.FaceModel.TriangleIndices
KeywordA : P:Microsoft.Kinect.Face.FaceModel.TriangleIndices
AssetID : P:Microsoft.Kinect.Face.FaceModel.TriangleIndices
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModel.TriangleIndices
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
