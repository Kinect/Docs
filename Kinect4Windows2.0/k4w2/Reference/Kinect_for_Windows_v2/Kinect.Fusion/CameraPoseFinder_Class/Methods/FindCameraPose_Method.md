CameraPoseFinder.FindCameraPose Method  
======================================  

Retrieves the poses in the camera pose finder database that are most similar to the current camera input. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
<a href="../../MatchCandidates_Class.md">MatchCandidates</a>^ FindCameraPose(  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>^ depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>^ colorFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public <a href="../../MatchCandidates_Class.md">MatchCandidates</a>FindCameraPose (  
         <a href="../../DepthFloatFrame_Class.md">DepthFloatFrame</a>depthFloatFrame,  
         <a href="../../ColorImageFrame_Class.md">ColorImageFrame</a>colorFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var matchCandidates = cameraPoseFinder.findCameraPose(depthFloatFrame, colorFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFloatFrame*    
Type: [DepthFloatFrame](../../DepthFloatFrame_Class.md)  
 The depth float frame to be processed. This frame must have valid camera parameters. Also, this frame must be the same size and have been captured at the same time as the *colorFrame* parameter.  

*colorFrame*    
Type: [ColorImageFrame](../../ColorImageFrame_Class.md)  
 The color frame to be processed. This frame must have valid camera parameters. Also, this frame must be the same size and have been captured at the same time as the *depthFloatFrame* parameter.  

<span id="ID4EP"></span>
#### Return value  

Type: [MatchCandidates](../../MatchCandidates_Class.md)  
 Returns a [MatchCandidates](../../MatchCandidates_Class.md) object that contains a set of matched frames and poses. These poses and similarity measurements are ordered in terms of decreasing similarity.  

<span id="ID4ELB"></span>

Exceptions  
==========  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Exception type</th>
<th align="left">Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.argumentexception.aspx">ArgumentException</a></td>
<td align="left">One of the following occurred:  
<ul>
<li>The <em>depthFloatFrame</em> or <em>colorFrame</em> parameter is an incorrect image size.</li>
<li>The image sizes of the <em>depthFloatFrame</em> and <em>colorFrame</em> parameters do not match.</li>
<li>The <a href="../../CameraParameters_Structure.md">CameraParameters</a> for the <em>depthFloatFrame</em> or <em>colorFrame</em> parameter is <strong>null</strong>.</li>
<li>The focal length of the <em>depthFloatFrame</em> or <em>colorFrame</em> parameter is an incorrect size.</li>
</ul></td>
</tr>
<tr class="even">
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.argumentnullexception.aspx">ArgumentNullException</a></td>
<td align="left">The <em>depthFloatFrame</em> or <em>colorFrame</em> parameter is <strong>null</strong>.</td>
</tr>
<tr class="odd">
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.invalidoperationexception.aspx">InvalidOperationException</a></td>
<td align="left">One of the following occurred:  
<ul>
<li>The Kinect Runtime could not be accessed.</li>
<li>The call failed for an unknown reason.</li>
</ul></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4ERD"></span>

See also  
========  

<span id="ID4ETD"></span>
#### Reference  

[CameraPoseFinder Class](../../CameraPoseFinder_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FindCameraPose Method
RLTitle : CameraPoseFinder.FindCameraPose Method
KeywordK : FindCameraPose method
KeywordK : CameraPoseFinder.FindCameraPose method
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.FindCameraPose
KeywordF : CameraPoseFinder.FindCameraPose
KeywordF : FindCameraPose
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.FindCameraPose(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame)
KeywordA : M:Microsoft.Kinect.Fusion.CameraPoseFinder.FindCameraPose(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame)
AssetID : M:Microsoft.Kinect.Fusion.CameraPoseFinder.FindCameraPose(Microsoft.Kinect.Fusion.DepthFloatFrame,Microsoft.Kinect.Fusion.ColorImageFrame)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinder.FindCameraPose
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
