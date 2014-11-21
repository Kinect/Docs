KinectEngagementMode Enumeration  
================================  

Enumerates the modes in which engaged users can be tracked. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectEngagementMode  
{  
    KinectEngagementMode_None = 0,  
    KinectEngagementMode_SystemOnePerson = 1,  
    KinectEngagementMode_SystemTwoPerson = 2,  
    KinectEngagementMode_ManualOnePerson = 3,  
    KinectEngagementMode_ManualTwoPerson = 4  
} KinectEngagementMode, KinectEngagementMode_None, KinectEngagementMode_SystemOnePerson, KinectEngagementMode_SystemTwoPerson, KinectEngagementMode_ManualOnePerson, KinectEngagementMode_ManualTwoPerson;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EHB"></span>

Constants  
=========  

| Constant                              | Description                                        |
|---------------------------------------|----------------------------------------------------|
| KinectEngagementMode\_None            | No engagement tracking.                            |
| KinectEngagementMode\_SystemOnePerson | The system dynamically detects one engaged person. |
| KinectEngagementMode\_SystemTwoPerson | The system dynamically detects two engaged people. |
| KinectEngagementMode\_ManualOnePerson | The app specifies one engaged person.              |
| KinectEngagementMode\_ManualTwoPerson | The app specifies two engaged people.              |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectEngagementMode Enumeration
RLTitle : KinectEngagementMode Enumeration
KeywordK : KinectEngagementMode enumeration
HelpPriority : 2
KeywordF : KinectEngagementMode
KeywordF : Microsoft.Kinect.kinect.KinectEngagementMode
KeywordA : T:Microsoft.Kinect.kinect.KinectEngagementMode
AssetID : T:Microsoft.Kinect.kinect.KinectEngagementMode
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectEngagementMode
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
