KinectHoldingState Enumeration  
==============================  

Specifies the state of the Holding event. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectHoldingState  
{  
    KinectHoldingState_Started = 0,  
    KinectHoldingState_Completed = 1,  
    KinectHoldingState_Canceled = 2  
} KinectHoldingState, KinectHoldingState_Started, KinectHoldingState_Completed, KinectHoldingState_Canceled;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant                      | Description                                                                                                                                                |
|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| KinectHoldingState\_Started   | A single contact has been detected and a time threshold is crossed without the contact being lifted, another contact detected, or another gesture started. |
| KinectHoldingState\_Completed | The single contact is lifted.                                                                                                                              |
| KinectHoldingState\_Canceled  | An additional contact is detected, a subsequent gesture (such as a slide) is detected, or the CompleteGesture method is called.                            |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectHoldingState Enumeration
RLTitle : KinectHoldingState Enumeration
KeywordK : KinectHoldingState enumeration
HelpPriority : 2
KeywordF : KinectHoldingState
KeywordF : Microsoft.Kinect.kinect.KinectHoldingState
KeywordA : T:Microsoft.Kinect.kinect.KinectHoldingState
AssetID : T:Microsoft.Kinect.kinect.KinectHoldingState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectHoldingState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
