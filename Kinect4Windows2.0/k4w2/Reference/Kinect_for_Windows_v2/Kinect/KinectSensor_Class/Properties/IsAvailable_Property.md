KinectSensor.IsAvailable Property  
=================================  

Gets whether the Kinect sensor is available and able to retrieve frames. <span id="syntaxSection"></span>

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
property bool IsAvailable {  
         bool get ();  
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
<td align="left"><pre><code>public bool IsAvailable { get; }</code></pre></td>
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
<td align="left"><pre><code>var isAvailable = kinectSensor.isAvailable;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ER"></span>
#### Property value  

[C++]   
 [C\#]   
 [JavaScript]   

Type: [bool](http://msdn.microsoft.com/en-us/library/hh755815.aspx)  
Type: [bool](http://msdn.microsoft.com/en-us/library/system.boolean.aspx)  
Type: Boolean  

Returns **true** if the Kinect sensor is available; **false** otherwise.  

<span id="remarks"></span>

Remarks  
=======  

Use **IsAvailable** to find out whether the sensor is able to get frames. **IsAvailable** will be **true** after calling [Open](../Methods/Open_Method.md).  

**IsAvailable** will become **false** after calling [Close](../Methods/Close_Method.md).  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E1B"></span>

See also  
========  

<span id="ID4E3B"></span>
#### Reference  

[KinectSensor Class](../../KinectSensor_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IsAvailable Property
RLTitle : KinectSensor.IsAvailable Property
KeywordK : IsAvailable property
KeywordK : KinectSensor.IsAvailable property
KeywordF : WindowsPreview.Kinect.KinectSensor.IsAvailable
KeywordF : KinectSensor.IsAvailable
KeywordF : IsAvailable
KeywordF : WindowsPreview.Kinect.KinectSensor.IsAvailable
KeywordA : P:WindowsPreview.Kinect.KinectSensor.IsAvailable
AssetID : P:WindowsPreview.Kinect.KinectSensor.IsAvailable
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectSensor.IsAvailable
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
