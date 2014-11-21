HandType Enumeration  
====================  

Enumerates the ways in which a hand can be identified. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _HandType  
{  
    HandType_NONE = 0,  
    HandType_LEFT = (HandType_NONE+1),  
    HandType_RIGHT = (HandType_LEFT+1)  
} HandType, HandType_NONE, HandType_LEFT, HandType_RIGHT;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant        | Description                                         |
|-----------------|-----------------------------------------------------|
| HandType\_NONE  | The hand is not identified as a right or left hand. |
| HandType\_LEFT  | The user's left hand.                               |
| HandType\_RIGHT | The user's right hand.                              |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HandType Enumeration
RLTitle : HandType Enumeration
KeywordK : HandType enumeration
HelpPriority : 2
KeywordF : HandType
KeywordF : Microsoft.Kinect.kinect.HandType
KeywordA : T:Microsoft.Kinect.kinect.HandType
AssetID : T:Microsoft.Kinect.kinect.HandType
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.HandType
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
