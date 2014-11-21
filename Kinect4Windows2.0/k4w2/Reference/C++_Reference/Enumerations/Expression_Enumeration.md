Expression Enumeration  
======================  

User expressions. Expression functionality is not supported for Kinect for Windows apps. This enumeration is included to support cross-compilation with the Xbox SDK. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _Expression  
{  
    Expression_Neutral = 0,  
    Expression_Happy = 1,  
    Expression_Count = (Expression_Happy+1)  
} Expression, Expression_Neutral, Expression_Happy, Expression_Count;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant            | Description                                             |
|---------------------|---------------------------------------------------------|
| Expression\_Neutral | No expression is present, or the expression is neutral. |
| Expression\_Happy   | The expression is happy.                                |
| Expression\_Count   | Max value; (Expression\_Happy+1)                        |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Expression Enumeration
RLTitle : Expression Enumeration
KeywordK : Expression enumeration
HelpPriority : 2
KeywordF : Expression
KeywordF : Microsoft.Kinect.kinect.Expression
KeywordA : T:Microsoft.Kinect.kinect.Expression
AssetID : T:Microsoft.Kinect.kinect.Expression
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.Expression
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
