CursorSpriteSheetDefinition Constructor (Uri, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)  
=================================================================================================================================  

Initializes a new instance of the [CursorSpriteSheetDefinition](../../CursorSpriteSheetDefinit.md) class. <span id="syntaxSection"></span>

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
CursorSpriteSheetDefinition(  
         Uri^ imageUri,  
         int32 columns,  
         int32 rows,  
         int32 width,  
         int32 height,  
         int32 pressDownStartFrame,  
         int32 pressDownEndFrame,  
         int32 pressingStartFrame,  
         int32 pressingEndFrame,  
         int32 pressHoldStartFrame,  
         int32 pressHoldEndFrame,  
         int32 grippingStartFrame,  
         int32 grippingEndFrame  
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
<td align="left"><pre><code>public CursorSpriteSheetDefinition (  
         UriimageUri,  
         int columns,  
         int rows,  
         int width,  
         int height,  
         int pressDownStartFrame,  
         int pressDownEndFrame,  
         int pressingStartFrame,  
         int pressingEndFrame,  
         int pressHoldStartFrame,  
         int pressHoldEndFrame,  
         int grippingStartFrame,  
         int grippingEndFrame  
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
<td align="left"><pre><code>var cursorSpriteSheetDefinition = new Microsoft.Kinect.Toolkit.Input.CursorSpriteSheetDefinition(imageUri, columns, rows, width, height, pressDownStartFrame, pressDownEndFrame, pressingStartFrame, pressingEndFrame, pressHoldStartFrame, pressHoldEndFrame, grippingStartFrame, grippingEndFrame);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*imageUri*    
[C++] Type: [Uri](http://msdn.microsoft.com/en-us/library/windows.foundation.uri.aspx)  
  [C\#] Type: [Uri](http://msdn.microsoft.com/en-us/library/system.uri.aspx)  
  [JavaScript] Type: [Uri](http://msdn.microsoft.com/en-us/library/windows.foundation.uri.aspx)  
   

The URI of the sprite sheet image.  

*columns*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The number of columns in the sprite sheet.  

*rows*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The number of rows in the sprite sheet.  

*width*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The width of a single sprite frame in the sprite sheet.  

*height*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The height of a single sprite frame in the sprite sheet.  

*pressDownStartFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The start frame within the sprite sheet of the foreground press down animation.  

*pressDownEndFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The final frame within the sprite sheet of the foreground press down animation.  

*pressingStartFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The start frame within the sprite sheet of the foreground animation.  

*pressingEndFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The final frame within the sprite sheet of the foreground animation.  

*pressHoldStartFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The start frame within the sprite sheet of the background press and hold animation.  

*pressHoldEndFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The end frame within the sprite sheet of the background press and hold animation.  

*grippingStartFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The start frame within the sprite sheet of the foreground gripping animation.  

*grippingEndFrame*    
[C++] Type: int32  
  [C\#] Type: [int](http://msdn.microsoft.com/en-us/library/system.int32.aspx)  
  [JavaScript] Type: Number  
   

The final frame within the sprite sheet of the foreground gripping animation.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4EJD"></span>

See also  
========  

<span id="ID4ELD"></span>
#### Reference  

[CursorSpriteSheetDefinition Class](../../CursorSpriteSheetDefinit.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CursorSpriteSheetDefinition Constructor (Uri, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)
RLTitle : CursorSpriteSheetDefinition Constructor (Uri, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32, Int32)
KeywordA : M:Microsoft.Kinect.Toolkit.Input.CursorSpriteSheetDefinition.#ctor(Windows.Foundation.Uri,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)
AssetID : M:Microsoft.Kinect.Toolkit.Input.CursorSpriteSheetDefinition.#ctor(Windows.Foundation.Uri,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,System.Int32)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.CursorSpriteSheetDefinition
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
