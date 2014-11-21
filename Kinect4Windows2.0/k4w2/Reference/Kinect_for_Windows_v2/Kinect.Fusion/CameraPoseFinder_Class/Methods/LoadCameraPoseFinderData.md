CameraPoseFinder.LoadCameraPoseFinderDatabase Method  
====================================================  

Loads a previously-saved camera pose finder database from disk. <span id="syntaxSection"></span>

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
void LoadCameraPoseFinderDatabase(  
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
<td align="left"><pre><code>public void LoadCameraPoseFinderDatabase (  
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
<td align="left"><pre><code>cameraPoseFinder.loadCameraPoseFinderDatabase(filename);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*filename*    
[C++] Type: [String](http://msdn.microsoft.com/en-us/library/hh755812.aspx)  
  [C\#] Type: [string](http://msdn.microsoft.com/en-us/library/system.string.aspx)  
  [JavaScript] Type: String  
   

The name of the camera pose finder database file to load.  

<span id="ID4EX"></span>

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
<td align="left"><a href="http://msdn.microsoft.com/en-us/library/system.invalidoperationexception.aspx">InvalidOperationException</a></td>
<td align="left">One of the following occurred:  
<ul>
<li>The Kinect Runtime could not be accessed.</li>
<li>The device is not connected.</li>
<li>The file specified by the <em>fileName</em> parameter could not be found.</li>
<li>The device does not have enough memory.</li>
<li>The call failed for an unknown reason.</li>
</ul></td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

All existing data is replaced on a successful load of the database. If the database is saved to disk alongside the reconstruction volume, you can restart and update reconstruction and tracking by reloading both files and then running the camera pose finder.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EYB"></span>

See also  
========  

<span id="ID4E1B"></span>
#### Reference  

[CameraPoseFinder Class](../../CameraPoseFinder_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : LoadCameraPoseFinderDatabase Method
RLTitle : CameraPoseFinder.LoadCameraPoseFinderDatabase Method
KeywordK : LoadCameraPoseFinderDatabase method
KeywordK : CameraPoseFinder.LoadCameraPoseFinderDatabase method
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.LoadCameraPoseFinderDatabase
KeywordF : CameraPoseFinder.LoadCameraPoseFinderDatabase
KeywordF : LoadCameraPoseFinderDatabase
KeywordF : Microsoft.Kinect.Fusion.CameraPoseFinder.LoadCameraPoseFinderDatabase(System.String)
KeywordA : M:Microsoft.Kinect.Fusion.CameraPoseFinder.LoadCameraPoseFinderDatabase(System.String)
AssetID : M:Microsoft.Kinect.Fusion.CameraPoseFinder.LoadCameraPoseFinderDatabase(System.String)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.CameraPoseFinder.LoadCameraPoseFinderDatabase
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
