KinectCapabilities Enumeration  
==============================  

Specifies the capabilities of the kinect sensor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectCapabilities  
{  
    KinectCapabilities_None = 0,  
    KinectCapabilities_Vision = 0x1,  
    KinectCapabilities_Audio = 0x2,  
    KinectCapabilities_Face = 0x4,  
    KinectCapabilities_Expressions = 0x8,  
    KinectCapabilities_Gamechat = 0x10  
} KinectCapabilities, KinectCapabilities_None, KinectCapabilities_Vision, KinectCapabilities_Audio, KinectCapabilities_Face, KinectCapabilities_Expressions, KinectCapabilities_Gamechat;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELB"></span>

Constants  
=========  

| Constant                        | Description                          |
|---------------------------------|--------------------------------------|
| KinectCapabilities\_None        | No kinect capabilites are supported. |
| KinectCapabilities\_Vision      | Vision is supported.                 |
| KinectCapabilities\_Audio       | Audio is supported.                  |
| KinectCapabilities\_Face        | Facial recognition is supported.     |
| KinectCapabilities\_Expressions | Expressions are supported.           |
| KinectCapabilities\_Gamechat    | Game chat is supported.              |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectCapabilities Enumeration
RLTitle : KinectCapabilities Enumeration
KeywordK : KinectCapabilities enumeration
HelpPriority : 2
KeywordF : KinectCapabilities
KeywordF : Microsoft.Kinect.kinect.KinectCapabilities
KeywordA : T:Microsoft.Kinect.kinect.KinectCapabilities
AssetID : T:Microsoft.Kinect.kinect.KinectCapabilities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectCapabilities
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
