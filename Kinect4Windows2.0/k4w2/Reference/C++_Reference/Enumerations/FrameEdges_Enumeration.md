FrameEdges Enumeration  
======================  

Identifies if the user's body is visible by indicating any portion of the user that is not in the camera's field of view. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FrameEdges  
{  
    FrameEdge_None = 0,  
    FrameEdge_Right = 0x1,  
    FrameEdge_Left = 0x2,  
    FrameEdge_Top = 0x4,  
    FrameEdge_Bottom = 0x8  
} FrameEdges, FrameEdge_None, FrameEdge_Right, FrameEdge_Left, FrameEdge_Top, FrameEdge_Bottom;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EHB"></span>

Constants  
=========  

| Constant          | Description                                                                              |
|-------------------|------------------------------------------------------------------------------------------|
| FrameEdge\_None   | None of the user's body is out of the camera's field of view, the user is fully visible. |
| FrameEdge\_Right  | The user's body extends to the right of the camera's field of view.                      |
| FrameEdge\_Left   | The user's body extends to the left of the camera's field of view.                       |
| FrameEdge\_Top    | The user's body extends below the camera's field of view.                                |
| FrameEdge\_Bottom | The user's body extends below the camera's field of view.                                |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameEdges Enumeration
RLTitle : FrameEdges Enumeration
KeywordK : FrameEdges enumeration
HelpPriority : 2
KeywordF : FrameEdges
KeywordF : Microsoft.Kinect.kinect.FrameEdges
KeywordA : T:Microsoft.Kinect.kinect.FrameEdges
AssetID : T:Microsoft.Kinect.kinect.FrameEdges
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.FrameEdges
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
