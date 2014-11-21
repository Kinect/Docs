InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates Method  
==============================================================================  

Transforms a pixel-based window coordinate into a pointer coordinate that is normalized between 0 and 1.0. <span id="syntaxSection"></span>

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
static Point TransformWindowCoordinatesToInputPointerCoordinates(  
         Point windowPoint,  
         Rect windowBounds  
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
<td align="left"><pre><code>public static Point TransformWindowCoordinatesToInputPointerCoordinates (  
         Point windowPoint,  
         Rect windowBounds  
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
<td align="left"><pre><code>var point = Microsoft.Kinect.Toolkit.Input.InputPointerManager.transformWindowCoordinatesToInputPointerCoordinates(windowPoint, windowBounds);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*windowPoint*    
Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The point to transform.  

*windowBounds*    
Type: [Rect](http://msdn.microsoft.com/en-us/library/windows.foundation.rect.aspx)  
The window bounds to use for the transform.  

<span id="ID4EQ"></span>
#### Return value  

Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The pointer coordinate.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[InputPointerManager Class](../../InputPointerManager_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TransformWindowCoordinatesToInputPointerCoordinates Method
RLTitle : InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates Method
KeywordK : TransformWindowCoordinatesToInputPointerCoordinates method
KeywordK : InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates method
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates
KeywordF : InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates
KeywordF : TransformWindowCoordinatesToInputPointerCoordinates
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates(Windows.Foundation.Point,Windows.Foundation.Rect)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates(Windows.Foundation.Point,Windows.Foundation.Rect)
AssetID : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates(Windows.Foundation.Point,Windows.Foundation.Rect)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformWindowCoordinatesToInputPointerCoordinates
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
