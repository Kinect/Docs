IVisualGestureBuilderFrameReference::AcquireFrame Method  
========================================================  

Gets the actual Visual Gesture Builder frame from the reference. <span id="syntaxSection"></span>

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
HRESULT AcquireFrame(  
         IVisualGestureBuilderFrame **gestureFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gestureFrame*    
Type: IVisualGestureBuilderFrame  
[out] The actual Visual Gesture Builder frame.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AcquireFrame Method
RLTitle : IVisualGestureBuilderFrameReference::AcquireFrame Method
KeywordK : AcquireFrame method
KeywordK : IVisualGestureBuilderFrameReference::AcquireFrame method
KeywordF : IVisualGestureBuilderFrameReference::AcquireFrame
KeywordF : AcquireFrame
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReference.AcquireFrame(IVisualGestureBuilderFrame@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReference.AcquireFrame(IVisualGestureBuilderFrame@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReference.AcquireFrame(IVisualGestureBuilderFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReference::AcquireFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
