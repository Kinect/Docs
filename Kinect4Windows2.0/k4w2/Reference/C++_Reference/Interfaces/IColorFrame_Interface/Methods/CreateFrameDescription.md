IColorFrame::CreateFrameDescription Method  
==========================================  

Creates a FrameDescription object for the ColorFrame of the requested format. <span id="syntaxSection"></span>

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
HRESULT CreateFrameDescription(  
         ColorImageFormat format,  
         IFrameDescription **frameDescription  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*format*    
Type: ColorImageFormat  
The image format for which to create the FrameDescription object.  

*frameDescription*    
Type: IFrameDescription  
[out] The frame description.  

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
TOCTitle : CreateFrameDescription Method
RLTitle : IColorFrame::CreateFrameDescription Method
KeywordK : CreateFrameDescription method
KeywordK : IColorFrame::CreateFrameDescription method
KeywordF : IColorFrame::CreateFrameDescription
KeywordF : CreateFrameDescription
KeywordF : Microsoft.Kinect.kinect.IColorFrame.CreateFrameDescription(ColorImageFormat,IFrameDescription@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrame.CreateFrameDescription(ColorImageFormat,IFrameDescription@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrame.CreateFrameDescription(ColorImageFormat,IFrameDescription@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrame::CreateFrameDescription
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
