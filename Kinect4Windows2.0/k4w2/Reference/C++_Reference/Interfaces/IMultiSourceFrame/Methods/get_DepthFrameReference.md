IMultiSourceFrame::get\_DepthFrameReference Method  
==================================================  

Gets the color frame reference of the multi source frame. <span id="syntaxSection"></span>

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
HRESULT get_DepthFrameReference(  
         IDepthFrameReference **depthFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrameReference*    
Type: IDepthFrameReference  
[out] The color frame reference of the multi source frame.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_DepthFrameReference Method
RLTitle : IMultiSourceFrame::get_DepthFrameReference Method
KeywordK : get_DepthFrameReference method
KeywordK : IMultiSourceFrame::get_DepthFrameReference method
KeywordF : IMultiSourceFrame::get_DepthFrameReference
KeywordF : get_DepthFrameReference
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrame.get_DepthFrameReference(IDepthFrameReference@)
KeywordA : M:Microsoft.Kinect.kinect.IMultiSourceFrame.get_DepthFrameReference(IDepthFrameReference@)
AssetID : M:Microsoft.Kinect.kinect.IMultiSourceFrame.get_DepthFrameReference(IDepthFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrame::get_DepthFrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
