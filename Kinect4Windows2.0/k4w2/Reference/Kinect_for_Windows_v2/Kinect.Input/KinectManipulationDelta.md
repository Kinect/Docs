KinectManipulationDelta Structure  
=================================  

Represents the accumulated transformations for the current manipulation. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public value struct KinectManipulationDelta</code></pre></td>
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
<td align="left"><pre><code>public struct KinectManipulationDelta</code></pre></td>
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
<td align="left"><pre><code>var kinectManipulationDelta = {  
      expansion : /* Your value */,   
      rotation : /* Your value */,   
      scale : /* Your value */,   
      translation : /* Your value */  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**KinectManipulationDelta** has the following members.  

<span id="publicfieldsSection"></span>

Fields  
======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="KinectManipulationDelta/KinectManipulationDelta/Expansion_Field.md">Expansion</a></td>
<td align="left">Manipulation expansion delta. This will always be 0.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectManipulationDelta/KinectManipulationDelta/Rotation_Field.md">Rotation</a></td>
<td align="left">The change in angle of rotation, in degrees. This will always be 0.</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectManipulationDelta/KinectManipulationDelta/Scale_Field.md">Scale</a></td>
<td align="left">The multiplicative change in zoom factor.</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectManipulationDelta/KinectManipulationDelta/Translation_Field.md">Translation</a></td>
<td align="left">The change in x and y screen coordinates, in the core window coordinate space (normalized [0,1]).</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EU"></span>

See also  
========  

<span id="ID4EW"></span>
#### Reference  

[WindowsPreview.Kinect.Input Namespace](../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectManipulationDelta Structure
RLTitle : KinectManipulationDelta Structure
KeywordK : KinectManipulationDelta structure, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationDelta
KeywordF : KinectManipulationDelta
KeywordF : WindowsPreview.Kinect.Input.KinectManipulationDelta
KeywordA : T:WindowsPreview.Kinect.Input.KinectManipulationDelta
AssetID : T:WindowsPreview.Kinect.Input.KinectManipulationDelta
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.KinectManipulationDelta
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
