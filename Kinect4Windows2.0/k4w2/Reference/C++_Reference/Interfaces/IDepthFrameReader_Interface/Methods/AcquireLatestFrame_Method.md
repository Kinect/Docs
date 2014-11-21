IDepthFrameReader::AcquireLatestFrame Method  
============================================  

Gets the most recent depth frame. <span id="syntaxSection"></span>

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
HRESULT AcquireLatestFrame(  
         IDepthFrame **depthFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrame*    
Type: IDepthFrame  
[out] The most recent depth frame.  

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
TOCTitle : AcquireLatestFrame Method
RLTitle : IDepthFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : IDepthFrameReader::AcquireLatestFrame method
KeywordF : IDepthFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.kinect.IDepthFrameReader.AcquireLatestFrame(IDepthFrame@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrameReader.AcquireLatestFrame(IDepthFrame@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrameReader.AcquireLatestFrame(IDepthFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
