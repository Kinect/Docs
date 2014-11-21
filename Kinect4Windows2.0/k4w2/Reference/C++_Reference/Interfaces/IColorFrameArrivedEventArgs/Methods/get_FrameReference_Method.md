IColorFrameArrivedEventArgs::get\_FrameReference Method  
=======================================================  

Gets the reference to the color frame for the FrameArrived event. <span id="syntaxSection"></span>

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
         IColorFrameReference **colorFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*colorFrameReference*    
Type: IColorFrameReference  
[out] The reference to the color frame for the FrameArrived event.  

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
RLTitle : IColorFrameArrivedEventArgs::get_FrameReference Method
KeywordK : get_FrameReference method
KeywordK : IColorFrameArrivedEventArgs::get_FrameReference method
KeywordF : IColorFrameArrivedEventArgs::get_FrameReference
KeywordF : get_FrameReference
KeywordF : Microsoft.Kinect.kinect.IColorFrameArrivedEventArgs.get_FrameReference(IColorFrameReference@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrameArrivedEventArgs.get_FrameReference(IColorFrameReference@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrameArrivedEventArgs.get_FrameReference(IColorFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrameArrivedEventArgs::get_FrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
