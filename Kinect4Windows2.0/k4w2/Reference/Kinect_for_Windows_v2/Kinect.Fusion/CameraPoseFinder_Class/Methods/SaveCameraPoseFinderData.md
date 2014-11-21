CameraPoseFinder.SaveCameraPoseFinderDatabase Method  
====================================================  

Saves the camera pose finder database to disk. <span id="syntaxSection"></span>

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
void SaveCameraPoseFinderDatabase(  
         String^ filename  
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
<td align="left"><pre><code>public void SaveCameraPoseFinderDatabase (  
         stringfilename  
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
<td align="left"><pre><code>cameraPoseFinder.saveCameraPoseFinderDatabase(filename);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*filename*    
[C++] Type: [String](http://msdn.microsoft.com/en-us/library/hh755812.aspx)  
  [C\#] Type: [string](http://msdn.microsoft.com/en-us/library/system.string.aspx)  
  [JavaScript] Type: String  
   

The filename of the database file to save to.  

<span id="remarks"></span>

Remarks  
=======  

If the database is saved to disk alongside the reconstruction volume, you can restart and update reconstruction and tracking by reloading both files and then running the camera pose finder.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EBB"></span>

See also  
========  

<span id="ID4EDB"></span>
#### Reference  

[CameraPoseFinder Class](../../CameraPoseFinder_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SaveCameraPoseFinderDatabase Method
RLTitle : CameraPoseFinder.SaveCameraPoseFinderDatabase Method
KeywordK : SaveCameraPoseFinderDatabase method
KeywordK : CameraPoseFinder.SaveCameraPoseFinderDatabase method
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.SaveCameraPoseFinderDatabase
KeywordF : CameraPoseFinder.SaveCameraPoseFinderDatabase
KeywordF : SaveCameraPoseFinderDatabase
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.SaveCameraPoseFinderDatabase(System.String)
KeywordA : M:Microsoft.Kinect.Fusion.CameraPoseFinder.SaveCameraPoseFinderDatabase(System.String)
AssetID : M:Microsoft.Kinect.Fusion.CameraPoseFinder.SaveCameraPoseFinderDatabase(System.String)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinder.SaveCameraPoseFinderDatabase
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
