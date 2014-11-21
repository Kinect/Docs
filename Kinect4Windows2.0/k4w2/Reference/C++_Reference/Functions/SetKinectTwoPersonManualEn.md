SetKinectTwoPersonManualEngagement  
==================================  

Sets the engagement mode to two person manual engagement. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT SetKinectTwoPersonManualEngagement(  
         IBodyHandPair *pBodyHandPair1,  
         IBodyHandPair *pBodyHandPair2  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pBodyHandPair1*    
Type: IBodyHandPair  
[in] The first body hand pair to be tracked as engaged.  

*pBodyHandPair2*    
Type: IBodyHandPair  
[in] The second body hand pair to be tracked as engaged.  

<span id="ID4EN"></span>
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
TOCTitle : SetKinectTwoPersonManualEngagement
RLTitle : SetKinectTwoPersonManualEngagement
KeywordK : SetKinectTwoPersonManualEngagement
KeywordF : SetKinectTwoPersonManualEngagement
KeywordF : Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement(IBodyHandPair,IBodyHandPair)
KeywordA : M:Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement(IBodyHandPair,IBodyHandPair)
AssetID : M:Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement(IBodyHandPair,IBodyHandPair)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
