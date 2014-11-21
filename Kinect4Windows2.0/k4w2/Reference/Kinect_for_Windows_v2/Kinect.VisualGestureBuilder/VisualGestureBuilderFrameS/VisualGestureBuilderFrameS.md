VisualGestureBuilderFrameSource Constructor  
===========================================  

Initializes a new instance of the [VisualGestureBuilderFrameSource](../VisualGestureBuilderFrameS.md) class. <span id="syntaxSection"></span>

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
VisualGestureBuilderFrameSource(  
         <a href="../../Kinect/KinectSensor_Class.md">KinectSensor</a>^ sensor,  
         uint64 initialTrackingId  
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
<td align="left"><pre><code>public VisualGestureBuilderFrameSource (  
         <a href="../../Kinect/KinectSensor_Class.md">KinectSensor</a>sensor,  
         ulong initialTrackingId  
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
<td align="left"><pre><code>var visualGestureBuilderFrameSource = new Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource(sensor, initialTrackingId);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*sensor*    
Type: [KinectSensor](../../Kinect/KinectSensor_Class.md)  
The Kinect sensor associated with the frame source.  

*initialTrackingId*    
[C++] Type: uint64  
  [C\#] Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
  [JavaScript] Type: Number  
   

The initial tracking ID.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.VisualGestureBuilder  
**Assembly:**Microsoft.Kinect.VisualGestureBuilder (in microsoft.kinect.visualgesturebuilder.dll)  

<span id="ID4EGB"></span>

See also  
========  

<span id="ID4EIB"></span>
#### Reference  

[VisualGestureBuilderFrameSource Class](../VisualGestureBuilderFrameS.md)  
 [Microsoft.Kinect.VisualGestureBuilder Namespace](../../Kinect.VisualGestureBuilder.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : VisualGestureBuilderFrameSource Constructor
RLTitle : VisualGestureBuilderFrameSource Constructor
KeywordK : VisualGestureBuilderFrameSource class, constructor
KeywordK : VisualGestureBuilderFrameSource.VisualGestureBuilderFrameSource constructor
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.#ctor
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.VisualGestureBuilderFrameSource
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.New
KeywordF : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.#ctor(WindowsPreview.Kinect.KinectSensor,System.UInt64)
KeywordF : VisualGestureBuilderFrameSource.VisualGestureBuilderFrameSource
KeywordF : VisualGestureBuilderFrameSource.New
KeywordA : M:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.#ctor(WindowsPreview.Kinect.KinectSensor,System.UInt64)
AssetID : M:Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource.#ctor(WindowsPreview.Kinect.KinectSensor,System.UInt64)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.visualgesturebuilder.dll
APIName : Microsoft.Kinect.VisualGestureBuilder.VisualGestureBuilderFrameSource
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
