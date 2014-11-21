BodyFrameSource.OverrideHandTracking Method  
===========================================  

Overloaded methods for OverrideHandTracking.  
<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><img src="../../../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>If you call the override with formerly invalid parameters, the call will no longer fail or throw exceptions at the WinRT layer.</p>
<p>Previously, calling the override with 0 or an unknown tracking ID, or specifying an unknown tracking ID as the replace parameter, would return an error. These calls will now succeed. Setting 0 or an unknown tracking ID will always remove the oldest override, and performing a set/replace sequence with an invalid replace will replace the oldest override.</p>
<p>If your title relies on calling these APIs with invalid arguments being a no-op, you must change its code.</p></td>
</tr>
</tbody>
</table>

<span id="overloadsSection"></span>

Overload list  
=============  

| Name                                                                                                  | Description                                                                                                          |
|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| [BodyFrameSource.OverrideHandTracking (UInt64)](OverrideHandTracking/OverrideHandTracking.md)         | Overrides the default behavior of tracking the hands of the nearest bodies to track the hands of the specified body. |
| [BodyFrameSource.OverrideHandTracking (UInt64, UInt64)](OverrideHandTracking/OverrideHandTracking.md) | Override hand tracking using the old and new tracking ids.                                                           |

<span id="ID4ES"></span>

See also  
========  

<span id="ID4EU"></span>
#### Reference  

[BodyFrameSource Class](../../BodyFrameSource_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OverrideHandTracking Method
RLTitle : BodyFrameSource.OverrideHandTracking Method
KeywordK : OverrideHandTracking method
KeywordK : BodyFrameSource.OverrideHandTracking method
KeywordF : WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking
KeywordF : BodyFrameSource.OverrideHandTracking
KeywordF : OverrideHandTracking
KeywordF : WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking
KeywordA : Overload:WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking
AssetID : Overload:WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyFrameSource.OverrideHandTracking
TargetOS : Windows
TopicType : kbSyntax
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
