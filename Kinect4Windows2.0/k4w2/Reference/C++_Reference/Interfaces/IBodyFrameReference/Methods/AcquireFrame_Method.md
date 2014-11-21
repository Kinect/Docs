IBodyFrameReference::AcquireFrame Method  
========================================  

Gets the actual body frame from the reference. <span id="syntaxSection"></span>

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
HRESULT AcquireFrame(  
         IBodyFrame **bodyFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bodyFrame*    
Type: IBodyFrame  
[out] The actual body frame from the reference.  

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
TOCTitle : AcquireFrame Method
RLTitle : IBodyFrameReference::AcquireFrame Method
KeywordK : AcquireFrame method
KeywordK : IBodyFrameReference::AcquireFrame method
KeywordF : IBodyFrameReference::AcquireFrame
KeywordF : AcquireFrame
KeywordF : Microsoft.Kinect.kinect.IBodyFrameReference.AcquireFrame(IBodyFrame@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrameReference.AcquireFrame(IBodyFrame@)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrameReference.AcquireFrame(IBodyFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameReference::AcquireFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
