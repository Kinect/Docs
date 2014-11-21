IManipulatableModel.ManipulationUpdated Event  
=============================================  

Occurs when the manipulation status of a manipulatable Kinect Toolkit input element has changed.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a>&gt;^ ManipulationUpdated {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a>&gt;^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationUpdatedE.md">KinectManipulationUpdatedEventArgs</a>&gt; ManipulationUpdated</code></pre></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[IManipulatableModel Interface](../../IManipulatableModel.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ManipulationUpdated Event
RLTitle : IManipulatableModel.ManipulationUpdated Event
KeywordK : ManipulationUpdated event
KeywordK : IManipulatableModel.ManipulationUpdated event
KeywordF : Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationUpdated
KeywordF : IManipulatableModel.ManipulationUpdated
KeywordF : ManipulationUpdated
KeywordF : Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationUpdated
KeywordA : E:Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationUpdated
AssetID : E:Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationUpdated
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationUpdated
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
