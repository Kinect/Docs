IBodyFrameSource::get\_BodyCount Method  
=======================================  

Gets the body count. <span id="syntaxSection"></span>

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
HRESULT get_BodyCount(  
         INT32 *bodyCount  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bodyCount*    
Type: INT32  
[out] The body count.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="remarks"></span>

Remarks  
=======  

The body count represents the number of bodies the system can track and thus the size of the collection that must be used to store these bodies.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_BodyCount Method
RLTitle : IBodyFrameSource::get_BodyCount Method
KeywordK : get_BodyCount method
KeywordK : IBodyFrameSource::get_BodyCount method
KeywordF : IBodyFrameSource::get_BodyCount
KeywordF : get_BodyCount
KeywordF : Microsoft.Kinect.kinect.IBodyFrameSource.get_BodyCount(INT32@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrameSource.get_BodyCount(INT32@)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrameSource.get_BodyCount(INT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameSource::get_BodyCount
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
