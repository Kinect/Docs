InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates Method  
==============================================================================  

Transforms a pointer coordinate that is normalized between 0 and 1.0 into a pixel-based window coordinate. <span id="syntaxSection"></span>

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
static Point TransformInputPointerCoordinatesToWindowCoordinates(  
         Point inputPointerPoint,  
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
<td align="left"><pre><code>public static Point TransformInputPointerCoordinatesToWindowCoordinates (  
         Point inputPointerPoint,  
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
<td align="left"><pre><code>var point = Microsoft.Kinect.Toolkit.Input.InputPointerManager.transformInputPointerCoordinatesToWindowCoordinates(inputPointerPoint, windowBounds);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*inputPointerPoint*    
Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The point to transform.  

*windowBounds*    
Type: [Rect](http://msdn.microsoft.com/en-us/library/windows.foundation.rect.aspx)  
The window bounds to use for the transform.  

<span id="ID4EQ"></span>
#### Return value  

Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The window coordinate.  

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
TOCTitle : TransformInputPointerCoordinatesToWindowCoordinates Method
RLTitle : InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates Method
KeywordK : TransformInputPointerCoordinatesToWindowCoordinates method
KeywordK : InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates method
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates
KeywordF : InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates
KeywordF : TransformInputPointerCoordinatesToWindowCoordinates
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates(Windows.Foundation.Point,Windows.Foundation.Rect)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates(Windows.Foundation.Point,Windows.Foundation.Rect)
AssetID : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates(Windows.Foundation.Point,Windows.Foundation.Rect)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.InputPointerManager.TransformInputPointerCoordinatesToWindowCoordinates
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
