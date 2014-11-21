KinectPointerPointTransform.TryTransform Method  
===============================================  

Attempts to transform the specified point and returns a value that indicates whether the transformation was successful. <span id="syntaxSection"></span>

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
bool TryTransform(  
         Point inPoint,  
         out Point outPoint  
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
<td align="left"><pre><code>public bool TryTransform (  
         Point inPoint,  
         out Point outPoint  
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
<td align="left"><pre><code>var boolean = kinectPointerPointTransform.tryTransform(inPoint, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*inPoint*    
Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The point to transform.  

*outPoint*    
Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The result of transforming inPoint.  

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
Type: Boolean  

True if inPoint was transformed; otherwise, false.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EGB"></span>

See also  
========  

<span id="ID4EIB"></span>
#### Reference  

[KinectPointerPointTransform Class](../../KinectPointerPointTransform.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TryTransform Method
RLTitle : KinectPointerPointTransform.TryTransform Method
KeywordK : TryTransform method
KeywordK : KinectPointerPointTransform.TryTransform method
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPointTransform.TryTransform
KeywordF : KinectPointerPointTransform.TryTransform
KeywordF : TryTransform
KeywordF : WindowsPreview.Kinect.Input.KinectPointerPointTransform.TryTransform(Windows.Foundation.Point,Windows.Foundation.Point@)
KeywordA : M:WindowsPreview.Kinect.Input.KinectPointerPointTransform.TryTransform(Windows.Foundation.Point,Windows.Foundation.Point@)
AssetID : M:WindowsPreview.Kinect.Input.KinectPointerPointTransform.TryTransform(Windows.Foundation.Point,Windows.Foundation.Point@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectPointerPointTransform.TryTransform
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
