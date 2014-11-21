ColorReconstruction.ImportVolumeBlock Method  
============================================  

Imports a reconstruction volume as a buffer of shorts, with color as an integer buffer. <span id="syntaxSection"></span>

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
void ImportVolumeBlock(  
         IBuffer^ volumeBlock,  
         IBuffer^ colorVolumeBlock  
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
<td align="left"><pre><code>public void ImportVolumeBlock (  
         IBuffervolumeBlock,  
         IBuffercolorVolumeBlock  
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
<td align="left"><pre><code>colorReconstruction.importVolumeBlock(volumeBlock, colorVolumeBlock);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*volumeBlock*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  

A pre-allocated short buffer filled with volume data. This buffer must equal the size of the current initialized reconstruction volume. The number of elements in this buffer should be allocated as (*destinationResolutionX*\**destinationResolutionY*\**destinationResolutionZ*). To access the voxel located at x,y,z use pVolume[z][y][x], or index as a one-dimensional array for a particular voxel (x,y,z) as follows (with pitch = x resolution, slice = (y resolution \* pitch)).  

    unsigned int index = (z * slice)  + (y * pitch) + x;  

| ![](../../../../../../resources/note.gif)Note                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A right handed coordinate system is used, with the origin of the volume (that is, voxel 0,0,0) at the top left of the front plane of the cube. Similar to bitmap images with top left origin, +X is to the right, +Y down, and +Z is forward from the origin into the reconstruction volume. |

*colorVolumeBlock*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
 A pre-allocated integer buffer filled with color volume data. The number of elements in this buffer must be the same as the number of elements in the *volumeBlock* buffer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4E1B"></span>

See also  
========  

<span id="ID4E3B"></span>
#### Reference  

[ColorReconstruction Class](../../ColorReconstruction_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ImportVolumeBlock Method
RLTitle : ColorReconstruction.ImportVolumeBlock Method
KeywordK : ImportVolumeBlock method
KeywordK : ColorReconstruction.ImportVolumeBlock method
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.ImportVolumeBlock
KeywordF : ColorReconstruction.ImportVolumeBlock
KeywordF : ImportVolumeBlock
KeywordF : Microsoft.Kinect.Fusion.ColorReconstruction.ImportVolumeBlock(Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer)
KeywordA : M:Microsoft.Kinect.Fusion.ColorReconstruction.ImportVolumeBlock(Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer)
AssetID : M:Microsoft.Kinect.Fusion.ColorReconstruction.ImportVolumeBlock(Windows.Storage.Streams.IBuffer,Windows.Storage.Streams.IBuffer)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.ColorReconstruction.ImportVolumeBlock
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
