GetFaceModelTriangles  
=====================  

Gets the face model triangle vertices. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT GetFaceModelTriangles(  
         UINT32 capacity,  
         UINT32 *triangeVertices  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT32  
The size of the triangleVertices array.  

*triangeVertices*    
Type: UINT32  
[out] An array in which the face model triangle vertices will be stored.  

<span id="ID4EN"></span>
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
TOCTitle : GetFaceModelTriangles
RLTitle : GetFaceModelTriangles
KeywordK : GetFaceModelTriangles
KeywordF : GetFaceModelTriangles
KeywordF : Microsoft.Kinect.face.GetFaceModelTriangles(UINT32,UINT32@)
KeywordA : M:Microsoft.Kinect.face.GetFaceModelTriangles(UINT32,UINT32@)
AssetID : M:Microsoft.Kinect.face.GetFaceModelTriangles(UINT32,UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.GetFaceModelTriangles
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
