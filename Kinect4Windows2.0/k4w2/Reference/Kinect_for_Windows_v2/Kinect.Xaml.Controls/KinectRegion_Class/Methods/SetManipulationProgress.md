KinectRegion.SetManipulationProgress Method  
===========================================  

Sets the manipulation progress for the [KinectRegion](../../KinectRegion_Class.md). <span id="syntaxSection"></span>

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
void SetManipulationProgress(  
         uint32 pointerId,  
         <a href="../../ManipulationProgress.md">ManipulationProgress</a> flags  
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
<td align="left"><pre><code>public void SetManipulationProgress (  
         uint pointerId,  
         <a href="../../ManipulationProgress.md">ManipulationProgress</a> flags  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*pointerId*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
   

The ID of the [KinectPointerPoint Class](../../../Kinect.Input/KinectPointerPoint_Class.md) associated with the manipulation.  

*flags*    
Type: [ManipulationProgress](../../ManipulationProgress.md)  
Flags indicating the progress of the manipulation.  

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Xaml.Controls  
**Assembly:** (in )  

<span id="ID4EQB"></span>

See also  
========  

<span id="ID4ESB"></span>
#### Reference  

[KinectRegion Class](../../KinectRegion_Class.md)  
 [Microsoft.Kinect.Xaml.Controls Namespace](../../../Kinect.Xaml.Controls.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SetManipulationProgress Method
RLTitle : KinectRegion.SetManipulationProgress Method
KeywordK : SetManipulationProgress method
KeywordK : KinectRegion.SetManipulationProgress method
KeywordF : Microsoft.Kinect.Xaml.Controls.KinectRegion.SetManipulationProgress
KeywordF : KinectRegion.SetManipulationProgress
KeywordF : SetManipulationProgress
KeywordF : Microsoft.Kinect.Xaml.Controls.KinectRegion.SetManipulationProgress(System.UInt32,Microsoft.Kinect.Xaml.Controls.ManipulationProgress)
KeywordA : M:Microsoft.Kinect.Xaml.Controls.KinectRegion.SetManipulationProgress(System.UInt32,Microsoft.Kinect.Xaml.Controls.ManipulationProgress)
AssetID : M:Microsoft.Kinect.Xaml.Controls.KinectRegion.SetManipulationProgress(System.UInt32,Microsoft.Kinect.Xaml.Controls.ManipulationProgress)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Xaml.Controls.KinectRegion.SetManipulationProgress
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
