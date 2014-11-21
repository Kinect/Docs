IManipulatableModel.ManipulationStarted Event  
=============================================  

Occurs when a manipulation gesture of a manipulatable Kinect Toolkit input element has started.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a>&gt;^ ManipulationStarted {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a>&gt;^ value);  
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../IManipulatableModel.md">IManipulatableModel</a>, <a href="../../../Kinect.Input/KinectManipulationStartedE.md">KinectManipulationStartedEventArgs</a>&gt; ManipulationStarted</code></pre></td>
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
TOCTitle : ManipulationStarted Event
RLTitle : IManipulatableModel.ManipulationStarted Event
KeywordK : ManipulationStarted event
KeywordK : IManipulatableModel.ManipulationStarted event
KeywordF : Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationStarted
KeywordF : IManipulatableModel.ManipulationStarted
KeywordF : ManipulationStarted
KeywordF : Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationStarted
KeywordA : E:Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationStarted
AssetID : E:Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationStarted
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.IManipulatableModel.ManipulationStarted
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
