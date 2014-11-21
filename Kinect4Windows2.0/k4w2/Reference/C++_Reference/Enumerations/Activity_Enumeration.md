Activity Enumeration  
====================  

The available activity types. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _Activity  
{  
    Activity_EyeLeftClosed = 0,  
    Activity_EyeRightClosed = 1,  
    Activity_MouthOpen = 2,  
    Activity_MouthMoved = 3,  
    Activity_LookingAway = 4,  
    Activity_Count = (Activity_LookingAway+1)  
} Activity, Activity_EyeLeftClosed, Activity_EyeRightClosed, Activity_MouthOpen, Activity_MouthMoved, Activity_LookingAway, Activity_Count;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELB"></span>

Constants  
=========  

| Constant                 | Description                                 |
|--------------------------|---------------------------------------------|
| Activity\_EyeLeftClosed  | The left eye is closed.                     |
| Activity\_EyeRightClosed | The right eye is closed.                    |
| Activity\_MouthOpen      | The mouth is open.                          |
| Activity\_MouthMoved     | The mouth is closed.                        |
| Activity\_LookingAway    | The person is looking away from the sensor. |
| Activity\_Count          | Max value; (Activity\_LookingAway+1) .      |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Activity Enumeration
RLTitle : Activity Enumeration
KeywordK : Activity enumeration
HelpPriority : 2
KeywordF : Activity
KeywordF : Microsoft.Kinect.kinect.Activity
KeywordA : T:Microsoft.Kinect.kinect.Activity
AssetID : T:Microsoft.Kinect.kinect.Activity
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.Activity
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
