CreateBodyHandPair  
==================  

Creates a new [IBodyHandPair](../Interfaces/IBodyHandPair_Interface.md) object representing a body/hand pair. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateBodyHandPair(  
         UINT64 bodyTrackingId,  
         HandType handType,  
         IBodyHandPair **ppBodyHandPair  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*bodyTrackingId*    
Type: UINT64  
The tracking ID of the body.  

*handType*    
Type: HandType  
The hand type.  

*ppBodyHandPair*    
Type: IBodyHandPair  
[out] The body/hand pair.  

<span id="ID4ER"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CreateBodyHandPair
RLTitle : CreateBodyHandPair
KeywordK : CreateBodyHandPair
KeywordF : CreateBodyHandPair
KeywordF : Microsoft.Kinect.kinect.CreateBodyHandPair(UINT64,HandType,IBodyHandPair@)
KeywordA : M:Microsoft.Kinect.kinect.CreateBodyHandPair(UINT64,HandType,IBodyHandPair@)
AssetID : M:Microsoft.Kinect.kinect.CreateBodyHandPair(UINT64,HandType,IBodyHandPair@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.CreateBodyHandPair
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
