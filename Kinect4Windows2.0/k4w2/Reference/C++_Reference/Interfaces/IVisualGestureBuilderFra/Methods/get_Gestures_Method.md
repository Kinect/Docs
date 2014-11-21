IVisualGestureBuilderFrameSource::get\_Gestures Method  
======================================================  

Gets a collection of gestures associated with the Visual Gesture Builder frame source. <span id="syntaxSection"></span>

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
HRESULT get_Gestures(  
         UINT capacity,  
         IGesture **gestures  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[in] The size of the array into which the gestures will be copied.  

*gestures*    
Type: IGesture  
[in, out] The array into which the gestures will be copied.  

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
TOCTitle : get_Gestures Method
RLTitle : IVisualGestureBuilderFrameSource::get_Gestures Method
KeywordK : get_Gestures method
KeywordK : IVisualGestureBuilderFrameSource::get_Gestures method
KeywordF : IVisualGestureBuilderFrameSource::get_Gestures
KeywordF : get_Gestures
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.get_Gestures(UINT,IGesture@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.get_Gestures(UINT,IGesture@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.get_Gestures(UINT,IGesture@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource::get_Gestures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
