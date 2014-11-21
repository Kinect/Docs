CameraPoseFinder Constructor (CameraPoseFinderParameters, UInt32)  
=================================================================  

Initializes a new instance of the [CameraPoseFinder](../../CameraPoseFinder_Class.md). <span id="syntaxSection"></span>

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
CameraPoseFinder(  
         <a href="../../CameraPoseFinderParameters.md">CameraPoseFinderParameters</a> cameraPoseFinderParameters,  
         uint32 seed  
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
<td align="left"><pre><code>public CameraPoseFinder (  
         <a href="../../CameraPoseFinderParameters.md">CameraPoseFinderParameters</a> cameraPoseFinderParameters,  
         uint seed  
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
<td align="left"><pre><code>var cameraPoseFinder = new Microsoft.Kinect.Fusion.CameraPoseFinder(cameraPoseFinderParameters, seed);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*cameraPoseFinderParameters*    
Type: [CameraPoseFinderParameters](../../CameraPoseFinderParameters.md)  
The parameters to use to initialize the object.  

*seed*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The number used to seed the random number generator used internally by the pose finder. If you wish to have reproduceable results between runs against the same camera pose finder data, set this to the same value for each run.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[CameraPoseFinder Class](../../CameraPoseFinder_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraPoseFinder Constructor (CameraPoseFinderParameters, UInt32)
RLTitle : CameraPoseFinder Constructor (CameraPoseFinderParameters, UInt32)
KeywordA : M:Microsoft.Kinect.Fusion.CameraPoseFinder.#ctor(Microsoft.Kinect.Fusion.CameraPoseFinderParameters,System.UInt32)
AssetID : M:Microsoft.Kinect.Fusion.CameraPoseFinder.#ctor(Microsoft.Kinect.Fusion.CameraPoseFinderParameters,System.UInt32)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinder
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
