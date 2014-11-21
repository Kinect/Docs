InputPointerManager.HandlePointerAsCursor Method  
================================================  

Instructs the input pointer manager to handle the pointer as a cursor. <span id="syntaxSection"></span>

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
<a href="../../HitTestResult_Class.md">HitTestResult</a>^ HandlePointerAsCursor(  
         <a href="../../../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a>^ kinectPointerPoint,  
         Rect bounds,  
         <a href="../../HitTestResult_Class.md">HitTestResult</a>^ hitTestResult  
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
<td align="left"><pre><code>public <a href="../../HitTestResult_Class.md">HitTestResult</a>HandlePointerAsCursor (  
         <a href="../../../Kinect.Input/KinectPointerPoint_Class.md">KinectPointerPoint</a>kinectPointerPoint,  
         Rect bounds,  
         <a href="../../HitTestResult_Class.md">HitTestResult</a>hitTestResult  
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
<td align="left"><pre><code>var hitTestResult = inputPointerManager.handlePointerAsCursor(kinectPointerPoint, bounds, hitTestResult);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*kinectPointerPoint*    
Type: [KinectPointerPoint](../../../Kinect.Input/KinectPointerPoint_Class.md)  
The pointer to use as a cursor.  

*bounds*    
Type: [Rect](http://msdn.microsoft.com/en-us/library/windows.foundation.rect.aspx)  
The region whithin which the cursor is confined.  

*hitTestResult*    
Type: [HitTestResult](../../HitTestResult_Class.md)  
The [HitTestResult](../../HitTestResult_Class.md) which will be updated with the input elements capture by the pointer.  

<span id="ID4EP"></span>
#### Return value  

Type: [HitTestResult](../../HitTestResult_Class.md)  
A [HitTestResult](../../HitTestResult_Class.md) containing the input elements captured by the pointer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EUB"></span>

See also  
========  

<span id="ID4EWB"></span>
#### Reference  

[InputPointerManager Class](../../InputPointerManager_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HandlePointerAsCursor Method
RLTitle : InputPointerManager.HandlePointerAsCursor Method
KeywordK : HandlePointerAsCursor method
KeywordK : InputPointerManager.HandlePointerAsCursor method
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.HandlePointerAsCursor
KeywordF : InputPointerManager.HandlePointerAsCursor
KeywordF : HandlePointerAsCursor
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.HandlePointerAsCursor(WindowsPreview.Kinect.Input.KinectPointerPoint,Windows.Foundation.Rect,Microsoft.Kinect.Toolkit.Input.HitTestResult)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.HandlePointerAsCursor(WindowsPreview.Kinect.Input.KinectPointerPoint,Windows.Foundation.Rect,Microsoft.Kinect.Toolkit.Input.HitTestResult)
AssetID : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.HandlePointerAsCursor(WindowsPreview.Kinect.Input.KinectPointerPoint,Windows.Foundation.Rect,Microsoft.Kinect.Toolkit.Input.HitTestResult)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.InputPointerManager.HandlePointerAsCursor
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
