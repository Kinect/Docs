KinectUserViewer.UpdateEngagement Method  
========================================  

Sets the tracking ID of the body and the hand type of the user that should be tracked as engaged. <span id="syntaxSection"></span>

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
void UpdateEngagement(  
         uint64 trackingID,  
         <a href="../../../Kinect.Input/HandType_Enumeration.md">HandType</a> handType  
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
<td align="left"><pre><code>public void UpdateEngagement (  
         ulong trackingID,  
         <a href="../../../Kinect.Input/HandType_Enumeration.md">HandType</a> handType  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*trackingID*    
[C++] Type: uint64  
  [C\#] Type: [ulong](http://msdn.microsoft.com/en-us/library/system.uint64.aspx)  
   

The ID of the body that should be tracked as engaged.  

*handType*    
Type: [HandType](../../../Kinect.Input/HandType_Enumeration.md)  
The hand type that should be tracked as engaged.  

<span id="remarks"></span>

Remarks  
=======  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Xaml.Controls  
**Assembly:** (in )  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[KinectUserViewer Class](../../KinectUserViewer_Class.md)  
 [Microsoft.Kinect.Xaml.Controls Namespace](../../../Kinect.Xaml.Controls.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : UpdateEngagement Method
RLTitle : KinectUserViewer.UpdateEngagement Method
KeywordK : UpdateEngagement method
KeywordK : KinectUserViewer.UpdateEngagement method
KeywordF : Microsoft.Kinect.Xaml.Controls.KinectUserViewer.UpdateEngagement
KeywordF : KinectUserViewer.UpdateEngagement
KeywordF : UpdateEngagement
KeywordF : Microsoft.Kinect.Xaml.Controls.KinectUserViewer.UpdateEngagement(System.UInt64,WindowsPreview.Kinect.Input.HandType)
KeywordA : M:Microsoft.Kinect.Xaml.Controls.KinectUserViewer.UpdateEngagement(System.UInt64,WindowsPreview.Kinect.Input.HandType)
AssetID : M:Microsoft.Kinect.Xaml.Controls.KinectUserViewer.UpdateEngagement(System.UInt64,WindowsPreview.Kinect.Input.HandType)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Xaml.Controls.KinectUserViewer.UpdateEngagement
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
