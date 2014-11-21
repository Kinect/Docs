IColorFrameReader::AcquireLatestFrame Method  
============================================  

Gets the most recent color frame. <span id="syntaxSection"></span>

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
         IColorFrame **colorFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*colorFrame*    
Type: IColorFrame  
[out] The most recent color frame.  

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
RLTitle : IColorFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : IColorFrameReader::AcquireLatestFrame method
KeywordF : IColorFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.kinect.IColorFrameReader.AcquireLatestFrame(IColorFrame@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrameReader.AcquireLatestFrame(IColorFrame@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrameReader.AcquireLatestFrame(IColorFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
