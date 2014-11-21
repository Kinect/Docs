IInfraredFrameArrivedEventArgs::get\_FrameReference Method  
==========================================================  

Gets the reference to the infrared frame for the FrameArrived event. <span id="syntaxSection"></span>

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
         IInfraredFrameReference **infraredFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*infraredFrameReference*    
Type: IInfraredFrameReference  
[out] The reference to the infrared frame for the FrameArrived event.  

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
TOCTitle : get_FrameReference Method
RLTitle : IInfraredFrameArrivedEventArgs::get_FrameReference Method
KeywordK : get_FrameReference method
KeywordK : IInfraredFrameArrivedEventArgs::get_FrameReference method
KeywordF : IInfraredFrameArrivedEventArgs::get_FrameReference
KeywordF : get_FrameReference
KeywordF : Microsoft.Kinect.kinect.IInfraredFrameArrivedEventArgs.get_FrameReference(IInfraredFrameReference@)
KeywordA : M:Microsoft.Kinect.kinect.IInfraredFrameArrivedEventArgs.get_FrameReference(IInfraredFrameReference@)
AssetID : M:Microsoft.Kinect.kinect.IInfraredFrameArrivedEventArgs.get_FrameReference(IInfraredFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrameArrivedEventArgs::get_FrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
