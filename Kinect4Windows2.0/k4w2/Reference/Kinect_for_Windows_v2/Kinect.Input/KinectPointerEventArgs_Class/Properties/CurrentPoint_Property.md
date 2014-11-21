KinectPointerEventArgs.CurrentPoint Property  
============================================  

Gets the pointer data of the last pointer event. <span id="syntaxSection"></span>

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
property <a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>^ CurrentPoint {  
         <a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>^ get ();  
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
<td align="left"><pre><code>public <a href="../../KinectPointerPoint_Class.md">KinectPointerPoint</a>CurrentPoint { get; }</code></pre></td>
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
<td align="left"><pre><code>var currentPoint = kinectPointerEventArgs.currentPoint;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

Type: [KinectPointerPoint](../../KinectPointerPoint_Class.md)  
Information about the state and screen position of the pointer.  

<span id="remarks"></span>

Remarks  
=======  

**CurrentPoint** corresponds to the last point retrieved by [GetIntermediatePoints](../Methods/GetIntermediatePoints_Method.md).  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[KinectPointerEventArgs Class](../../KinectPointerEventArgs_Class.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CurrentPoint Property
RLTitle : KinectPointerEventArgs.CurrentPoint Property
KeywordK : CurrentPoint property
KeywordK : KinectPointerEventArgs.CurrentPoint property
KeywordF : WindowsPreview.Kinect.Input.KinectPointerEventArgs.CurrentPoint
KeywordF : KinectPointerEventArgs.CurrentPoint
KeywordF : CurrentPoint
KeywordF : WindowsPreview.Kinect.Input.KinectPointerEventArgs.CurrentPoint
KeywordA : P:WindowsPreview.Kinect.Input.KinectPointerEventArgs.CurrentPoint
AssetID : P:WindowsPreview.Kinect.Input.KinectPointerEventArgs.CurrentPoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPointerEventArgs.CurrentPoint
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
