IBodyFrame::GetAndRefreshBodyData Method  
========================================  

Gets refreshed body data. <span id="syntaxSection"></span>

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
HRESULT GetAndRefreshBodyData(  
         UINT capacity,  
         IBody **bodies  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
The size of the body data.  

*bodies*    
Type: IBody  
[in, out] Refreshed body data.  

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
TOCTitle : GetAndRefreshBodyData Method
RLTitle : IBodyFrame::GetAndRefreshBodyData Method
KeywordK : GetAndRefreshBodyData method
KeywordK : IBodyFrame::GetAndRefreshBodyData method
KeywordF : IBodyFrame::GetAndRefreshBodyData
KeywordF : GetAndRefreshBodyData
KeywordF : Microsoft.Kinect.kinect.IBodyFrame.GetAndRefreshBodyData(UINT,IBody@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrame.GetAndRefreshBodyData(UINT,IBody@)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrame.GetAndRefreshBodyData(UINT,IBody@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrame::GetAndRefreshBodyData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
