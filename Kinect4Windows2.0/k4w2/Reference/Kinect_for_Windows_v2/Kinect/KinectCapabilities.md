KinectCapabilities Enumeration  
==============================  

Capabilities of the Kinect sensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>[FlagsAttribute]  
public enum class KinectCapabilities</code></pre></td>
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum KinectCapabilities</code></pre></td>
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
<td align="left"><pre><code>var kinectCapabilities = WindowsPreview.Kinect.KinectCapabilities.audio;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EDC"></span>

Members  
=======  

| Member          | Value | Description                      |
|-----------------|-------|----------------------------------|
| **Audio**       | 2     | Audio is supported.              |
| **Expressions** | 8     | Expressions are supported.       |
| **Face**        | 4     | Facial recognition is supported. |
| **Gamechat**    | 16    | Game chat is supported.          |
| **None**        | 0     | No capabilities are supported.   |
| **Vision**      | 1     | Vision is supported.             |

<span id="remarks"></span>

Remarks  
=======  

A title declares these capabilities in the **mx:Capability** element in its application manifest file.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ESC"></span>

See also  
========  

<span id="ID4EUC"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectCapabilities Enumeration
RLTitle : KinectCapabilities Enumeration
KeywordK : KinectCapabilities enumeration
KeywordK : WindowsPreview.Kinect.KinectCapabilities enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.KinectCapabilities
KeywordF : KinectCapabilities
KeywordF : WindowsPreview.Kinect.KinectCapabilities
KeywordA : T:WindowsPreview.Kinect.KinectCapabilities
AssetID : T:WindowsPreview.Kinect.KinectCapabilities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectCapabilities
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
