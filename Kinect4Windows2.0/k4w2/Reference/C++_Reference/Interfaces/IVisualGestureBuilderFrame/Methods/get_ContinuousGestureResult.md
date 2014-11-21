IVisualGestureBuilderFrame::get\_ContinuousGestureResult Method  
===============================================================  

Gets a continuous gesture result for the supplied gesture. <span id="syntaxSection"></span>

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
HRESULT get_ContinuousGestureResult(  
         IGesture *gesture,  
         _COM_Outptr_result_maybenull_ IContinuousGestureResult **result  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gesture*    
Type: IGesture  
[in] The gesture for which results should be retrieved.  

*result*    
Type: \_COM\_Outptr\_result\_maybenull\_ IContinuousGestureResult  
The discrete gesture result. This value may be null.  

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
TOCTitle : get_ContinuousGestureResult Method
RLTitle : IVisualGestureBuilderFrame::get_ContinuousGestureResult Method
KeywordK : get_ContinuousGestureResult method
KeywordK : IVisualGestureBuilderFrame::get_ContinuousGestureResult method
KeywordF : IVisualGestureBuilderFrame::get_ContinuousGestureResult
KeywordF : get_ContinuousGestureResult
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame.get_ContinuousGestureResult(IGesture,_COM_Outptr_result_maybenull_ IContinuousGestureResult)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame.get_ContinuousGestureResult(IGesture,_COM_Outptr_result_maybenull_ IContinuousGestureResult)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame.get_ContinuousGestureResult(IGesture,_COM_Outptr_result_maybenull_ IContinuousGestureResult)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame::get_ContinuousGestureResult
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
