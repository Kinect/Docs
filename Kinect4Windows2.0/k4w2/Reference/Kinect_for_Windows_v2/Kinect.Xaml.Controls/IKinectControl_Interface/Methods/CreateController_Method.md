IKinectControl.CreateController Method  
======================================  

Creates a [IKinectController](../../IKinectController_Interface.md) object with the specified input model and Kinect region. <span id="syntaxSection"></span>

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
<a href="../../IKinectController_Interface.md">IKinectController</a>^ CreateController(  
         <a href="../../../Kinect.Toolkit.Input/IInputModel_Interface.md">IInputModel</a>^ inputModel,  
         <a href="../../KinectRegion_Class.md">KinectRegion</a>^ kinectRegion  
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
<td align="left"><pre><code>public <a href="../../IKinectController_Interface.md">IKinectController</a>CreateController (  
         <a href="../../../Kinect.Toolkit.Input/IInputModel_Interface.md">IInputModel</a>inputModel,  
         <a href="../../KinectRegion_Class.md">KinectRegion</a>kinectRegion  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*inputModel*    
Type: [IInputModel](../../../Kinect.Toolkit.Input/IInputModel_Interface.md)  
The input model.  

*kinectRegion*    
Type: [KinectRegion](../../KinectRegion_Class.md)  
The Kinect region.  

<span id="ID4EU"></span>
#### Return value  

Type: [IKinectController](../../IKinectController_Interface.md)  
 The new [IKinectController](../../IKinectController_Interface.md) object.  

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Xaml.Controls  
**Assembly:** (in )  

<span id="ID4EWB"></span>

See also  
========  

<span id="ID4EYB"></span>
#### Reference  

[IKinectControl Interface](../../IKinectControl_Interface.md)  
 [Microsoft.Kinect.Xaml.Controls Namespace](../../../Kinect.Xaml.Controls.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CreateController Method
RLTitle : IKinectControl.CreateController Method
KeywordK : CreateController method
KeywordK : IKinectControl.CreateController method
KeywordF : Microsoft.Kinect.Xaml.Controls.IKinectControl.CreateController
KeywordF : IKinectControl.CreateController
KeywordF : CreateController
KeywordF : Microsoft.Kinect.Xaml.Controls.IKinectControl.CreateController(Microsoft.Kinect.Toolkit.Input.IInputModel,Microsoft.Kinect.Xaml.Controls.KinectRegion)
KeywordA : M:Microsoft.Kinect.Xaml.Controls.IKinectControl.CreateController(Microsoft.Kinect.Toolkit.Input.IInputModel,Microsoft.Kinect.Xaml.Controls.KinectRegion)
AssetID : M:Microsoft.Kinect.Xaml.Controls.IKinectControl.CreateController(Microsoft.Kinect.Toolkit.Input.IInputModel,Microsoft.Kinect.Xaml.Controls.KinectRegion)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Xaml.Controls.IKinectControl.CreateController
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
