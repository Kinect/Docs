IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData Method  
================================================================  

Calculates frame data for the high definition face frame source. <span id="syntaxSection"></span>

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
HRESULT FeedAndCalculateFrameData(  
         IBody *body,  
         UINT infraredCapacity,  
         UINT16 *infraredFrameBuffer,  
         UINT colorCapacity,  
         BYTE *colorFrameBuffer,  
         UINT depthCapacity,  
         UINT16 *depthFrameBuffer  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*body*    
Type: IBody  
[in] The body to use for the calculation.  

*infraredCapacity*    
Type: UINT  
The size of the infrared frame buffer.  

*infraredFrameBuffer*    
Type: UINT16  
[in] The infrared frame buffer to use for the calculation.  

*colorCapacity*    
Type: UINT  
The size of the color frame buffer.  

*colorFrameBuffer*    
Type: BYTE  
[in] The color frame buffer to use for the calculation.  

*depthCapacity*    
Type: UINT  
The size of the depth frame buffer.  

*depthFrameBuffer*    
Type: UINT16  
[in] The depth frame buffer to use for the calculation.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FeedAndCalculateFrameData Method
RLTitle : IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData Method
KeywordK : FeedAndCalculateFrameData method
KeywordK : IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData method
KeywordF : IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData
KeywordF : FeedAndCalculateFrameData
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.FeedAndCalculateFrameData(IBody,UINT,UINT16,UINT,BYTE,UINT,UINT16)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.FeedAndCalculateFrameData(IBody,UINT,UINT16,UINT,BYTE,UINT,UINT16)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.FeedAndCalculateFrameData(IBody,UINT,UINT16,UINT,BYTE,UINT,UINT16)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
