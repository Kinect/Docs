KinectPointerEventArgs.GetIntermediatePoints Method  
===================================================  

Retrieves the pointer data for up to the last 64 pointer locations since the last pointer event. <span id="syntaxSection"></span>

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
IVector&lt;<a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>&gt;^ GetIntermediatePoints()</code></pre></td>
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
<td align="left"><pre><code>public IList&lt;<a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>&gt;GetIntermediatePoints ()</code></pre></td>
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
<td align="left"><pre><code>var iVector = kinectPointerEventArgs.getIntermediatePoints();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[KinectPointerPoint](../../KinectPointerPoint_Class.md)\>
Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6.aspx)\<[KinectPointerPoint](../../KinectPointerPoint_Class.md)\>
Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[KinectPointerPoint](../../KinectPointerPoint_Class.md)\>

The data for each pointer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[KinectPointerEventArgs Class](../../KinectPointerEventArgs.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetIntermediatePoints Method
RLTitle : KinectPointerEventArgs.GetIntermediatePoints Method
KeywordK : GetIntermediatePoints method
KeywordK : KinectPointerEventArgs.GetIntermediatePoints method
KeywordF : WindowsPreview.Kinect.Input.KinectPointerEventArgs.GetIntermediatePoints
KeywordF : KinectPointerEventArgs.GetIntermediatePoints
KeywordF : GetIntermediatePoints
KeywordF : WindowsPreview.Kinect.Input.KinectPointerEventArgs.GetIntermediatePoints
KeywordA : M:WindowsPreview.Kinect.Input.KinectPointerEventArgs.GetIntermediatePoints
AssetID : M:WindowsPreview.Kinect.Input.KinectPointerEventArgs.GetIntermediatePoints
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPointerEventArgs.GetIntermediatePoints
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
