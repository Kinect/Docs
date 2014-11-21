IKinectGestureRecognizer::ProcessDownEvent Method  
=================================================  

Processes pointer input and raises the [IKinectGestureRecognizer](../../IKinectGestureRecognizer.md) events appropriate to a pointer down action for the gestures and manipulations specified by the object's gesture settings. <span id="syntaxSection"></span>

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
HRESULT ProcessDownEvent(  
         IKinectPointerPoint *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*value*    
Type: IKinectPointerPoint  
[in] The input point.  

<span id="ID4ET"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessDownEvent Method
RLTitle : IKinectGestureRecognizer::ProcessDownEvent Method
KeywordK : ProcessDownEvent method
KeywordK : IKinectGestureRecognizer::ProcessDownEvent method
KeywordF : IKinectGestureRecognizer::ProcessDownEvent
KeywordF : ProcessDownEvent
KeywordF : Microsoft.Kinect.kinect.IKinectGestureRecognizer.ProcessDownEvent(IKinectPointerPoint)
KeywordA : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.ProcessDownEvent(IKinectPointerPoint)
AssetID : M:Microsoft.Kinect.kinect.IKinectGestureRecognizer.ProcessDownEvent(IKinectPointerPoint)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectGestureRecognizer::ProcessDownEvent
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
