IVisualGestureBuilderFrameArrivedEventArgs::get\_FrameReference Method  
======================================================================  

Gets the Visual Gesture Builder frame reference associated with the event. <span id="syntaxSection"></span>

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
HRESULT get_FrameReference(  
         IVisualGestureBuilderFrameReference **gestureFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gestureFrameReference*    
Type: IVisualGestureBuilderFrameReference  
[out] The Visual Gesture Builder frame reference associated with the event.  

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
TOCTitle : get_FrameReference Method
RLTitle : IVisualGestureBuilderFrameArrivedEventArgs::get_FrameReference Method
KeywordK : get_FrameReference method
KeywordK : IVisualGestureBuilderFrameArrivedEventArgs::get_FrameReference method
KeywordF : IVisualGestureBuilderFrameArrivedEventArgs::get_FrameReference
KeywordF : get_FrameReference
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameArrivedEventArgs.get_FrameReference(IVisualGestureBuilderFrameReference@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameArrivedEventArgs.get_FrameReference(IVisualGestureBuilderFrameReference@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameArrivedEventArgs.get_FrameReference(IVisualGestureBuilderFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameArrivedEventArgs::get_FrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
