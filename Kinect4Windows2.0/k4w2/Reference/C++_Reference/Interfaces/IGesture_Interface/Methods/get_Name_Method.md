IGesture::get\_Name Method  
==========================  

The name of the gesture. <span id="syntaxSection"></span>

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
HRESULT get_Name(  
         UINT bufferSize,  
         wchar_t *gestureName  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bufferSize*    
Type: UINT  
The size of the buffer where the name will be copied.  

*gestureName*    
Type: wchar\_t  
[out] The buffer where the name will be copied.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_Name Method
RLTitle : IGesture::get_Name Method
KeywordK : get_Name method
KeywordK : IGesture::get_Name method
KeywordF : IGesture::get_Name
KeywordF : get_Name
KeywordF : Microsoft.Kinect.visualgesturebuilder.IGesture.get_Name(UINT,wchar_t@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IGesture.get_Name(UINT,wchar_t@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IGesture.get_Name(UINT,wchar_t@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IGesture::get_Name
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
