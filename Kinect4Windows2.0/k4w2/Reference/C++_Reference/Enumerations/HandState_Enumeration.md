HandState Enumeration  
=====================  

Indentifies possible hand states. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _HandState  
{  
    HandState_Unknown = 0,  
    HandState_NotTracked = 1,  
    HandState_Open = 2,  
    HandState_Closed = 3,  
    HandState_Lasso = 4  
} HandState, HandState_Unknown, HandState_NotTracked, HandState_Open, HandState_Closed, HandState_Lasso;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EHB"></span>

Constants  
=========  

| Constant              | Description                       |
|-----------------------|-----------------------------------|
| HandState\_Unknown    | The state of the hand in unknown. |
| HandState\_NotTracked | Hand state is not tracked.        |
| HandState\_Open       | The hand is open.                 |
| HandState\_Closed     | The hand is closed.               |
| HandState\_Lasso      | The hand is in the lasso state.   |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HandState Enumeration
RLTitle : HandState Enumeration
KeywordK : HandState enumeration
HelpPriority : 2
KeywordF : HandState
KeywordF : Microsoft.Kinect.kinect.HandState
KeywordA : T:Microsoft.Kinect.kinect.HandState
AssetID : T:Microsoft.Kinect.kinect.HandState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.HandState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
