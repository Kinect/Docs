FaceFrameSource Constructor  
===========================  

Initializes a new instance of the FaceFrameSource class. <span id="syntaxSection"></span>

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
FaceFrameSource(  
         <a href="../../Kinect/KinectSensor_Class.md">KinectSensor</a>^ sensor,  
         uint64 initialTrackingId,  
         <a href="../FaceFrameFeatures.md">FaceFrameFeatures</a> initialFaceFrameFeatures  
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
<td align="left"><pre><code>public FaceFrameSource (  
         <a href="../../Kinect/KinectSensor_Class.md">KinectSensor</a>sensor,  
         ulong initialTrackingId,  
         <a href="../FaceFrameFeatures.md">FaceFrameFeatures</a> initialFaceFrameFeatures  
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
<td align="left"><pre><code>var faceFrameSource = new Microsoft.Kinect.Face.FaceFrameSource(sensor, sensor, initialTrackingId, initialFaceFrameFeatures);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sensor*    
Type: [KinectSensor](../../Kinect/KinectSensor_Class.md)  
The Kinect sensor.  

*initialTrackingId*    
[C++] Type: uint64  
  [C\#] Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
  [JavaScript] Type: Number  
   

The initial tracking ID.  

*initialFaceFrameFeatures*    
Type: [FaceFrameFeatures](../FaceFrameFeatures.md)  
The initial face frame features.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EQB"></span>

See also  
========  

<span id="ID4ESB"></span>
#### Reference  

[FaceFrameSource Class](../FaceFrameSource_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameSource Constructor
RLTitle : FaceFrameSource Constructor
KeywordK : FaceFrameSource class, constructor
KeywordK : FaceFrameSource.FaceFrameSource constructor
KeywordF : Microsoft.Kinect.Face.FaceFrameSource.#ctor
KeywordF : Microsoft.Kinect.Face.FaceFrameSource.FaceFrameSource
KeywordF : Microsoft.Kinect.Face.FaceFrameSource.New
KeywordF : Microsoft.Kinect.Face.FaceFrameSource.#ctor(WindowsPreview.Kinect.KinectSensor,Windows.Kinect.KinectSensor,System.UInt64,Microsoft.Kinect.Face.FaceFrameFeatures)
KeywordF : FaceFrameSource.FaceFrameSource
KeywordF : FaceFrameSource.New
KeywordA : M:Microsoft.Kinect.Face.FaceFrameSource.#ctor(WindowsPreview.Kinect.KinectSensor,Windows.Kinect.KinectSensor,System.UInt64,Microsoft.Kinect.Face.FaceFrameFeatures)
AssetID : M:Microsoft.Kinect.Face.FaceFrameSource.#ctor(WindowsPreview.Kinect.KinectSensor,Windows.Kinect.KinectSensor,System.UInt64,Microsoft.Kinect.Face.FaceFrameFeatures)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameSource
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
