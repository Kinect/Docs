AudioBeamFrameList Class  
========================  

Represents a list of audio beam frames. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class AudioBeamFrameList sealed : IVectorView&lt;<a href="AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;, IIterable&lt;<a href="AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;, IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioBeamFrameList : IReadOnlyList&lt;<a href="AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;, IEnumerable&lt;<a href="AudioBeamFrame_Class.md">AudioBeamFrame</a>&gt;, IDisposable</code></pre></td>
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
<td align="left"><pre><code>var audioBeamFrameList = WindowsPreview.Kinect.AudioBeamFrameList;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**AudioBeamFrameList** has the following members.  

<span id="publicpropertiesSection"></span>

Properties  
==========  

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
<td align="left"><a href="AudioBeamFrameList_Class/Properties/Size_Property.md">Size</a></td>
<td align="left">Gets the size of the audio beam list.</td>
</tr>
</tbody>
</table>

<span id="publicmethodsSection"></span>

Methods  
=======  

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
<td align="left"><a href="AudioBeamFrameList_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Releases system resources associated with the audio beam frame list.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameList_Class/Methods/First_Method.md">First</a></td>
<td align="left">Gets the head frame in the audio beam frame list.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeamFrameList_Class/Methods/GetAt_Method.md">GetAt</a></td>
<td align="left">Retrieves an audio beam frame at a specified index in the list.</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameList_Class/Methods/GetMany_Method.md">GetMany</a></td>
<td align="left">Retrieves the audio beam frames that start at the specified index in the audio beam frame list.</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioBeamFrameList_Class/Methods/IndexOf_Method.md">IndexOf</a></td>
<td align="left">Retrieves the zero-based index of the first occurrence of the specified audio beam frame in the audio beam frame list.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioBeamFrameList Class
RLTitle : AudioBeamFrameList Class
KeywordK : AudioBeamFrameList class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList
KeywordF : AudioBeamFrameList
KeywordF : WindowsPreview.Kinect.AudioBeamFrameList
KeywordA : T:WindowsPreview.Kinect.AudioBeamFrameList
AssetID : T:WindowsPreview.Kinect.AudioBeamFrameList
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameList
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
