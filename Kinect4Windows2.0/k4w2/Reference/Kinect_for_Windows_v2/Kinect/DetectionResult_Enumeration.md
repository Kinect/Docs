DetectionResult Enumeration  
===========================  

Gesture detection result options. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public enum class DetectionResult</code></pre></td>
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
<td align="left"><pre><code>public enum DetectionResult</code></pre></td>
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
<td align="left"><pre><code>var detectionResult = WindowsPreview.Kinect.DetectionResult.maybe;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EPB"></span>

Members  
=======  

| Member      | Value | Description                                                    |
|-------------|-------|----------------------------------------------------------------|
| **Maybe**   | 2     | The appearance or activity might be a gesture.                 |
| **No**      | 1     | The appearance or activity is not a gesture.                   |
| **Unknown** | 0     | It is unknown whether the appearance or activity is a gesture. |
| **Yes**     | 3     | The appearance or activity is a gesture.                       |

<span id="remarks"></span>

Remarks  
=======  

This enumeration is used in a collection of properties such as [Activities](Body_Class/Properties/Activities_Property.md) and [Appearance](Body_Class/Properties/Appearance_Property.md).  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ECC"></span>

See also  
========  

<span id="ID4EEC"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DetectionResult Enumeration
RLTitle : DetectionResult Enumeration
KeywordK : DetectionResult enumeration
KeywordK : WindowsPreview.Kinect.DetectionResult enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.DetectionResult
KeywordF : DetectionResult
KeywordF : WindowsPreview.Kinect.DetectionResult
KeywordA : T:WindowsPreview.Kinect.DetectionResult
AssetID : T:WindowsPreview.Kinect.DetectionResult
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.DetectionResult
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
