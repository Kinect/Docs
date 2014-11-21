InputPointerManager.CompleteGestures Method (UInt32)  
====================================================  

Completes all in-progress gestures associated with the specified [KinectPointerPoint Class](../../../../Kinect.Input/KinectPointerPoint_Class.md). <span id="syntaxSection"></span>

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
void CompleteGestures(  
         uint32 pointerId  
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
<td align="left"><pre><code>public void CompleteGestures (  
         uint pointerId  
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
<td align="left"><pre><code>inputPointerManager.completeGestures(pointerId);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*pointerId*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The identifier of the [KinectPointerPoint Class](../../../../Kinect.Input/KinectPointerPoint_Class.md) object for which the gestures should be completed.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EFB"></span>

See also  
========  

<span id="ID4EHB"></span>
#### Reference  

[InputPointerManager Class](../../../InputPointerManager_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CompleteGestures Method (UInt32)
RLTitle : InputPointerManager.CompleteGestures Method (UInt32)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGestures(System.UInt32)
AssetID : M:Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGestures(System.UInt32)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.InputPointerManager.CompleteGestures
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
