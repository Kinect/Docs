CursorModel.Update Method  
=========================  

Updates the position and state of the cursor. <span id="syntaxSection"></span>

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
void Update(  
         Point pointInWindowCoordinates,  
         <a href="../../../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a>^ kinectPointerPoint,  
         <a href="../../PressableModel_Class.md">PressableModel</a>^ pressCapturedElement,  
         <a href="../../ManipulatableModel_Class.md">ManipulatableModel</a>^ manipulatableCapturedElement  
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
<td align="left"><pre><code>public void Update (  
         Point pointInWindowCoordinates,  
         <a href="../../../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a>kinectPointerPoint,  
         <a href="../../PressableModel_Class.md">PressableModel</a>pressCapturedElement,  
         <a href="../../ManipulatableModel_Class.md">ManipulatableModel</a>manipulatableCapturedElement  
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
<td align="left"><pre><code>cursorModel.update(pointInWindowCoordinates, kinectPointerPoint, pressCapturedElement, manipulatableCapturedElement);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pointInWindowCoordinates*    
Type: [Point](http://msdn.microsoft.com/en-us/library/windows.foundation.point.aspx)  
The position of the cursor, in window coordinates.  

*kinectPointerPoint*    
Type: [KinectPointerPoint](../../../Kinect.Input/KinectPointerPoint_Class.md)  
The [KinectPointerPoint Class](../../../Kinect.Input/KinectPointerPoint_Class.md) associated with the cursor.  

*pressCapturedElement*    
Type: [PressableModel](../../PressableModel_Class.md)  
An object representing a UI element that supports press gestures. This value will be null if the captured element does not support press gestures.  

*manipulatableCapturedElement*    
Type: [ManipulatableModel](../../ManipulatableModel_Class.md)  
An object representing a UI element that supports manipulation gestures. This value will be null if the captured element does not support manipulation gestures.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4ESB"></span>

See also  
========  

<span id="ID4EUB"></span>
#### Reference  

[CursorModel Class](../../CursorModel_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Update Method
RLTitle : CursorModel.Update Method
KeywordK : Update method
KeywordK : CursorModel.Update method
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorModel.Update
KeywordF : CursorModel.Update
KeywordF : Update
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorModel.Update(Windows.Foundation.Point,WindowsPreview.Kinect.Input.KinectPointerPoint,Microsoft.Kinect.Toolkit.Input.PressableModel,Microsoft.Kinect.Toolkit.Input.ManipulatableModel)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.CursorModel.Update(Windows.Foundation.Point,WindowsPreview.Kinect.Input.KinectPointerPoint,Microsoft.Kinect.Toolkit.Input.PressableModel,Microsoft.Kinect.Toolkit.Input.ManipulatableModel)
AssetID : M:Microsoft.Kinect.Toolkit.Input.CursorModel.Update(Windows.Foundation.Point,WindowsPreview.Kinect.Input.KinectPointerPoint,Microsoft.Kinect.Toolkit.Input.PressableModel,Microsoft.Kinect.Toolkit.Input.ManipulatableModel)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.CursorModel.Update
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
