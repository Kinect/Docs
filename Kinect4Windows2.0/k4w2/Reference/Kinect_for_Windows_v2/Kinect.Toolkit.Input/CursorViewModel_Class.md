CursorViewModel Class  
=====================  

Represents the presentation logic and state of a Kinect cursor. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public ref class CursorViewModel sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class CursorViewModel : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var cursorViewModel = Microsoft.Kinect.Toolkit.Input.CursorViewModel;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**CursorViewModel** has the following members.  

<span id="publicconstructorsSection"></span>

Constructors  
============  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Constructor.md">CursorViewModel</a></td>
<td align="left">Initializes a new instance of the <a href="">CursorViewModel</a> class.</td>
</tr>
</tbody>
</table>

<span id="publicpropertiesSection"></span>

Properties  
==========  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/Model_Property.md">Model</a></td>
<td align="left">Gets the <a href="CursorModel_Class.md">CursorModel Class</a> associated with the <a href="">CursorViewModel</a>.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/OriginPositionX_Property.md">OriginPositionX</a></td>
<td align="left">Gets the X coordinate of the origin of the sprite, in pixels, within a sprite frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/OriginPositionY_Property.md">OriginPositionY</a></td>
<td align="left">Gets the Y coordinate of the origin of the sprite, in pixels, within a sprite frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/ScaleTransformX_Property.md">ScaleTransformX</a></td>
<td align="left">Gets the horizontal scale transform of the sprite.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetBackgroundColumn.md">SpriteSheetBackgroundColumn</a></td>
<td align="left">Gets the column of the current background sprite frame within the sprite sheet.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetBackgroundIndex.md">SpriteSheetBackgroundIndex</a></td>
<td align="left">Gets the index within the sprite sheet of the current background sprite frame.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetBackgroundRow.md">SpriteSheetBackgroundRow</a></td>
<td align="left">Gets the row of the current background sprite frame within the sprite sheet.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetBackgroundX.md">SpriteSheetBackgroundX</a></td>
<td align="left">Gets the X coordinate, in pixels, of the current background sprite frame within the sprite sheet.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetBackgroundY.md">SpriteSheetBackgroundY</a></td>
<td align="left">Gets the Y coordinate, in pixels, of the current background sprite frame within the sprite sheet.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetForegroundColumn.md">SpriteSheetForegroundColumn</a></td>
<td align="left">Gets the column of the current foreground sprite frame within the sprite sheet.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetForegroundIndex.md">SpriteSheetForegroundIndex</a></td>
<td align="left">Gets the index within the sprite sheet of the current foreground sprite frame.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetForegroundRow.md">SpriteSheetForegroundRow</a></td>
<td align="left">Gets the row of the current foreground sprite frame within the sprite sheet.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetForegroundX.md">SpriteSheetForegroundX</a></td>
<td align="left">Gets the X coordinate, in pixels, of the current foreground sprite frame within the sprite sheet.</td>
</tr>
<tr class="even">
<td align="left"><a href="CursorViewModel_Class/Properties/SpriteSheetForegroundY.md">SpriteSheetForegroundY</a></td>
<td align="left">Gets the Y coordinate, in pixels, of the current foreground sprite frame within the sprite sheet.</td>
</tr>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Properties/TintColor_Property.md">TintColor</a></td>
<td align="left">Gets or sets the tint color of a Kinect cursor.</td>
</tr>
</tbody>
</table>

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="CursorViewModel_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Disposes of the object and associated resources.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EZ"></span>

See also  
========  

<span id="ID4E2"></span>
#### Reference  

[Microsoft.Kinect.Toolkit.Input Namespace](../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CursorViewModel Class
RLTitle : CursorViewModel Class
KeywordK : CursorViewModel class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorViewModel
KeywordF : CursorViewModel
KeywordF : Microsoft.Kinect.Toolkit.Input.CursorViewModel
KeywordA : T:Microsoft.Kinect.Toolkit.Input.CursorViewModel
AssetID : T:Microsoft.Kinect.Toolkit.Input.CursorViewModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.CursorViewModel
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
