InputPointerManager.CompleteGesture Method  
==========================================  

Completes a gesture associated with the specified [KinectPointerPoint Class](../../../Kinect.Input/KinectPointerPoint_Class.md) and Kinect Toolkit input element. <span id="syntaxSection"></span>

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
void CompleteGesture(  
         uint32 pointerId,  
         <a href="../../IInputModel_Interface.md">IInputModel</a>^ model  
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
<td align="left"><pre><code>public void CompleteGesture (  
         uint pointerId,  
         <a href="../../IInputModel_Interface.md">IInputModel</a>model  
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
<td align="left"><pre><code>inputPointerManager.completeGesture(pointerId, model);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*pointerId*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The identifier of the [KinectPointerPoint Class](../../../Kinect.Input/KinectPointerPoint_Class.md) object for which the gesture should be completed.  

*model*    
Type: [IInputModel](../../IInputModel_Interface.md)  
The Kinect Toolkit input element for the gesture should be completed.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EKB"></span>

See also  
========  

<span id="ID4EMB"></span>
#### Reference  

[InputPointerManager Class](../../InputPointerManager_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CompleteGesture Method
RLTitle : InputPointerManager.CompleteGesture Method
KeywordK : CompleteGesture method
KeywordK : InputPointerManager.CompleteGesture method
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGesture
KeywordF : InputPointerManager.CompleteGesture
KeywordF : CompleteGesture
KeywordF : Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGesture(System.UInt32,Microsoft.Kinect.Toolkit.Input.IInputModel)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGesture(System.UInt32,Microsoft.Kinect.Toolkit.Input.IInputModel)
AssetID : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGesture(System.UInt32,Microsoft.Kinect.Toolkit.Input.IInputModel)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGesture
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
