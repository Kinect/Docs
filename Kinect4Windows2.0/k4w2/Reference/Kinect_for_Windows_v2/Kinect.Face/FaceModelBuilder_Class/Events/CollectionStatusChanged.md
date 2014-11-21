FaceModelBuilder.CollectionStatusChanged Event  
==============================================  

Occurs when the collection status changes.<span id="syntaxSection"></span>

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
event TypedEventHandler&lt;<a href="../../FaceModelBuilder_Class.md">FaceModelBuilder</a>, <a href="../../CollectionStatusChangedEve.md">CollectionStatusChangedEventArgs</a>&gt;^ CollectionStatusChanged {  
         EventRegistrationToken add (TypedEventHandler&lt;<a href="../../FaceModelBuilder_Class.md">FaceModelBuilder</a>, <a href="../../CollectionStatusChangedEve.md">CollectionStatusChangedEventArgs</a>&gt;^ value);  
         void remove (EventRegistrationToken token);  
}</code></pre></td>
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
<td align="left"><pre><code>public event TypedEventHandler&lt;<a href="../../FaceModelBuilder_Class.md">FaceModelBuilder</a>, <a href="../../CollectionStatusChangedEve.md">CollectionStatusChangedEventArgs</a>&gt; CollectionStatusChanged</code></pre></td>
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
<td align="left"><pre><code>function onCollectionStatusChanged(eventArgs) { /* Your code */ }  

// addEventListener syntax  
faceModelBuilder.addEventListener(&quot;collectionstatuschanged&quot;, onCollectionStatusChanged);  
faceModelBuilder.removeEventListener(&quot;collectionstatuschanged&quot;, onCollectionStatusChanged);  

- or -  

faceModelBuilder.oncollectionstatuschanged = onCollectionStatusChanged;</code></pre></td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EX"></span>

See also  
========  

<span id="ID4EZ"></span>
#### Reference  

[FaceModelBuilder Class](../../FaceModelBuilder_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CollectionStatusChanged Event
RLTitle : FaceModelBuilder.CollectionStatusChanged Event
KeywordK : CollectionStatusChanged event
KeywordK : FaceModelBuilder.CollectionStatusChanged event
KeywordF : Microsoft.Kinect.Face.FaceModelBuilder.CollectionStatusChanged
KeywordF : FaceModelBuilder.CollectionStatusChanged
KeywordF : CollectionStatusChanged
KeywordF : Microsoft.Kinect.Face.FaceModelBuilder.CollectionStatusChanged
KeywordA : E:Microsoft.Kinect.Face.FaceModelBuilder.CollectionStatusChanged
AssetID : E:Microsoft.Kinect.Face.FaceModelBuilder.CollectionStatusChanged
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModelBuilder.CollectionStatusChanged
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
