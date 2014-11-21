BodyHandPair Constructor (UInt64, HandType)  
===========================================  

Initializes a new instance of the [BodyHandPair](../../BodyHandPair_Class.md) class with the specified body tracking ID and hand type.. <span id="syntaxSection"></span>

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
BodyHandPair(  
         uint64 bodyTrackingId,  
         <a href="../../HandType_Enumeration.md">HandType</a> handType  
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
<td align="left"><pre><code>public BodyHandPair (  
         ulong bodyTrackingId,  
         <a href="../../HandType_Enumeration.md">HandType</a> handType  
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
<td align="left"><pre><code>var bodyHandPair = new WindowsPreview.Kinect.Input.BodyHandPair(bodyTrackingId, handType);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*bodyTrackingId*    
[C++] Type: uint64  
  [C\#] Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
  [JavaScript] Type: Number  
   

The body tracking ID.  

*handType*    
Type: [HandType](../../HandType_Enumeration.md)  
The hand type.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect.Input  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EHB"></span>

See also  
========  

<span id="ID4EJB"></span>
#### Reference  

[BodyHandPair Class](../../BodyHandPair_Class.md)  
 [WindowsPreview.Kinect.Input Namespace](../../../Kinect.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : BodyHandPair Constructor (UInt64, HandType)
RLTitle : BodyHandPair Constructor (UInt64, HandType)
KeywordA : M:WindowsPreview.Kinect.Input.BodyHandPair.#ctor(System.UInt64,WindowsPreview.Kinect.Input.HandType)
AssetID : M:WindowsPreview.Kinect.Input.BodyHandPair.#ctor(System.UInt64,WindowsPreview.Kinect.Input.HandType)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.Input.BodyHandPair
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
