KinectGestureSettings Enumeration  
=================================  

Specifies the interactions that are supported by an Kinect for Windows application. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectGestureSettings  
{  
    KinectGestureSettings_None = 0,  
    KinectGestureSettings_Tap = 0x1,  
    KinectGestureSettings_ManipulationTranslateX = 0x40,  
    KinectGestureSettings_ManipulationTranslateY = 0x80,  
    KinectGestureSettings_ManipulationTranslateRailsX = 0x100,  
    KinectGestureSettings_ManipulationTranslateRailsY = 0x200,  
    KinectGestureSettings_ManipulationScale = 0x800,  
    KinectGestureSettings_ManipulationTranslateInertia = 0x1000,  
    KinectGestureSettings_KinectHold = 0x10000  
} KinectGestureSettings, KinectGestureSettings_None, KinectGestureSettings_Tap, KinectGestureSettings_ManipulationTranslateX, KinectGestureSettings_ManipulationTranslateY, KinectGestureSettings_ManipulationTranslateRailsX, KinectGestureSettings_ManipulationTranslateRailsY, KinectGestureSettings_ManipulationScale, KinectGestureSettings_ManipulationTranslateInertia, KinectGestureSettings_KinectHold;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EXB"></span>

Constants  
=========  

| Constant                                            | Description                                                                                                                                                                                                                                                                                     |
|-----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| KinectGestureSettings\_None                         | Disable support for gestures and manipulations.                                                                                                                                                                                                                                                 |
| KinectGestureSettings\_Tap                          | Enable support for the tap gesture.                                                                                                                                                                                                                                                             |
| KinectGestureSettings\_ManipulationTranslateX       | Enable support for the slide gesture through pointer input, on the horizontal axis. The ManipulationStarted, ManipulationUpdated, and ManipulationCompleted events are all raised during the course of this interaction. This gesture can be used for rearranging objects.                      |
| KinectGestureSettings\_ManipulationTranslateY       | Enable support for the slide gesture through pointer input, on the vertical axis. The ManipulationStarted, ManipulationUpdated, and ManipulationCompleted events are all raised during the course of this interaction. This gesture can be used for rearranging objects.                        |
| KinectGestureSettings\_ManipulationTranslateRailsX  | Enable support for the slide gesture through pointer input, on the horizontal axis using rails (guides). The ManipulationStarted, ManipulationUpdated, and ManipulationCompleted events are all raised during the course of this interaction. This gesture can be used for rearranging objects. |
| KinectGestureSettings\_ManipulationTranslateRailsY  | Enable support for the slide gesture through pointer input, on the vertical axis using rails (guides). The ManipulationStarted, ManipulationUpdated, and ManipulationCompleted events are all raised during the course of this interaction. This gesture can be used for rearranging objects.   |
| KinectGestureSettings\_ManipulationScale            | Enable support for the pinch or stretch gesture through pointer input. These gestures can be used for optical or semantic zoom and resizing an object. The ManipulationStarted, ManipulationUpdated, and ManipulationCompleted events are all raised during the course of this interaction.     |
| KinectGestureSettings\_ManipulationTranslateInertia | Enable support for scaling inertia after the pinch or stretch gesture (through pointer input) is complete. The ManipulationInertiaStarting event is raised if inertia is enabled.                                                                                                               |
| KinectGestureSettings\_KinectHold                   | Enable support for the press and hold gesture through Kinect gestures. The Holding event is raised if a time threshold is crossed before the user moves the hand cursor away from the UI element. This gesture can be used to display a context menu.                                           |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectGestureSettings Enumeration
RLTitle : KinectGestureSettings Enumeration
KeywordK : KinectGestureSettings enumeration
HelpPriority : 2
KeywordF : KinectGestureSettings
KeywordF : Microsoft.Kinect.kinect.KinectGestureSettings
KeywordA : T:Microsoft.Kinect.kinect.KinectGestureSettings
AssetID : T:Microsoft.Kinect.kinect.KinectGestureSettings
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectGestureSettings
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
