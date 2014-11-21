BodyFrameSource.OverrideHandTracking Method (UInt64, UInt64)  
============================================================  

Override hand tracking using the old and new tracking ids. <span id="syntaxSection"></span>

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
void OverrideHandTracking(  
         uint64 oldTrackingId,  
         uint64 newTrackingId  
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
<td align="left"><pre><code>public void OverrideHandTracking (  
         ulong oldTrackingId,  
         ulong newTrackingId  
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
<td align="left"><pre><code>bodyFrameSource.overrideHandTracking(oldTrackingId, newTrackingId);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*oldTrackingId*    
[C++] Type: uint64  
  [C\#] Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
  [JavaScript] Type: Number  
   

The old tracking id.  

*newTrackingId*    
[C++] Type: uint64  
  [C\#] Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
  [JavaScript] Type: Number  
   

The new tracking id.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EDB"></span>

See also  
========  

<span id="ID4EFB"></span>
#### Reference  

[BodyFrameSource Class](../../../BodyFrameSource_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OverrideHandTracking Method (UInt64, UInt64)
RLTitle : BodyFrameSource.OverrideHandTracking Method (UInt64, UInt64)
KeywordA : M:WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking(System.UInt64,System.UInt64)
AssetID : M:WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking(System.UInt64,System.UInt64)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking
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
