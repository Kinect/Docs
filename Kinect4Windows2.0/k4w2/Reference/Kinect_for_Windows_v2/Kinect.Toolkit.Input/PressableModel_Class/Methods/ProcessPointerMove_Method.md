PressableModel.ProcessPointerMove Method  
========================================  

Processes the movement of the pointer associated with the Kinect Toolkit input element. <span id="syntaxSection"></span>

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
bool ProcessPointerMove(  
         <a href="../../../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a>^ pointerPoint,  
         IMap&lt;uint32, <a href="../../HitTestResult_Class.md">HitTestResult</a>, <a href="../../HitTestResult_Class.md">HitTestResult</a>&gt;^ captureMap,  
         bool forceEndPress  
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
<td align="left"><pre><code>public bool ProcessPointerMove (  
         <a href="../../../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a>pointerPoint,  
         IDictionary&lt;uint, <a href="../../HitTestResult_Class.md">HitTestResult</a>, <a href="../../HitTestResult_Class.md">HitTestResult</a>&gt;captureMap,  
         bool forceEndPress  
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
<td align="left"><pre><code>var boolean = pressableModel.processPointerMove(pointerPoint, captureMap, forceEndPress);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pointerPoint*    
Type: [KinectPointerPoint](../../../Kinect.Input/KinectPointerPoint_Class.md)  
 The [KinectPointerPoint Class](../../../Kinect.Input/KinectPointerPoint_Class.md) associated with the pointer move event.  

*captureMap*    
[C++] Type: [IMap](http://msdn.microsoft.com/en-us/library/br226042.aspx)\<uint32, [HitTestResult](../../HitTestResult_Class.md), [HitTestResult](../../HitTestResult_Class.md)\>
  [C\#] Type: [IDictionary](http://msdn.microsoft.com/en-us/library/s4ys34ea.aspx)\<[uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx), [HitTestResult](../../HitTestResult_Class.md), [HitTestResult](../../HitTestResult_Class.md)\>
  [JavaScript] Type: [IMap](http://msdn.microsoft.com/en-us/library/br226042.aspx)\<Number, [HitTestResult](../../HitTestResult_Class.md), [HitTestResult](../../HitTestResult_Class.md)\>
   

A map of [KinectPointerPoint.PointerId Property](../../../Kinect.Input/KinectPointerPoint_Class/Properties/PointerId_Property.md) values to objects indicating the hit test results associated with each pointer point.  

*forceEndPress*    
[C++] Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
  [C\#] Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
  [JavaScript] Type: Boolean  
   

A boolean value indicating whether an ongoing press gesture should be ended.  

<span id="ID4EP"></span>
#### Return value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
Type: Boolean  

A boolean value indicating if the input element was captured during the pointer move event. True if the element was captured; otherwise, false.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4E4B"></span>

See also  
========  

<span id="ID4E6B"></span>
#### Reference  

[PressableModel Class](../../PressableModel_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessPointerMove Method
RLTitle : PressableModel.ProcessPointerMove Method
KeywordK : ProcessPointerMove method
KeywordK : PressableModel.ProcessPointerMove method
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.ProcessPointerMove
KeywordF : PressableModel.ProcessPointerMove
KeywordF : ProcessPointerMove
KeywordF : Microsoft.Kinect.Toolkit.Input.PressableModel.ProcessPointerMove(WindowsPreview.Kinect.Input.KinectPointerPoint,Windows.Foundation.Collections.IMap{System.UInt32,Microsoft.Kinect.Toolkit.Input.HitTestResult,Microsoft.Kinect.Toolkit.Input.HitTestResult},System.Boolean)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.PressableModel.ProcessPointerMove(WindowsPreview.Kinect.Input.KinectPointerPoint,Windows.Foundation.Collections.IMap{System.UInt32,Microsoft.Kinect.Toolkit.Input.HitTestResult,Microsoft.Kinect.Toolkit.Input.HitTestResult},System.Boolean)
AssetID : M:Microsoft.Kinect.Toolkit.Input.PressableModel.ProcessPointerMove(WindowsPreview.Kinect.Input.KinectPointerPoint,Windows.Foundation.Collections.IMap{System.UInt32,Microsoft.Kinect.Toolkit.Input.HitTestResult,Microsoft.Kinect.Toolkit.Input.HitTestResult},System.Boolean)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.PressableModel.ProcessPointerMove
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
