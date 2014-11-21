VisualGestureBuilderFrameSource.GetIsEnabled Method  
===================================================  

Gets a value indicating if the specified gesture is enabled for the Visual Gesture Builder frame source. <span id="syntaxSection"></span>

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
void GetIsEnabled(  
         <a href="../../Gesture_Class.md">Gesture</a>^ gesture,  
         out bool isEnabled  
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
<td align="left"><pre><code>public void GetIsEnabled (  
         <a href="../../Gesture_Class.md">Gesture</a>gesture,  
         out bool isEnabled  
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
<td align="left"><pre><code>visualGestureBuilderFrameSource.getIsEnabled(gesture, );</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gesture*    
Type: [Gesture](../../Gesture_Class.md)  
The gesture.  

*isEnabled*    
[C++] Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
  [C\#] Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
  [JavaScript] Type: Boolean  
   

True if the gesture is enabled; otherwise false.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4ECB"></span>

See also  
========  

<span id="ID4EEB"></span>
#### Reference  

[VisualGestureBuilderFrameSource Class](../../VisualGestureBuilderFrameS.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../../Kinect.VisualGestureBuilder.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetIsEnabled Method
RLTitle : VisualGestureBuilderFrameSource.GetIsEnabled Method
KeywordK : GetIsEnabled method
KeywordK : VisualGestureBuilderFrameSource.GetIsEnabled method
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.GetIsEnabled
KeywordF : VisualGestureBuilderFrameSource.GetIsEnabled
KeywordF : GetIsEnabled
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.GetIsEnabled(Microsoft.Kinect.VisualGestureBuilder.Gesture,System.Boolean@)
KeywordA : M:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.GetIsEnabled(Microsoft.Kinect.VisualGestureBuilder.Gesture,System.Boolean@)
AssetID : M:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.GetIsEnabled(Microsoft.Kinect.VisualGestureBuilder.Gesture,System.Boolean@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.GetIsEnabled
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
