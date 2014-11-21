IFaceModelBuilder Interface  
===========================  

Represents a face model builder. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IFaceModelBuilder : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IFaceModelBuilder** has the following members.  

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
<td align="left"><a href="IFaceModelBuilder/Methods/BeginFaceDataCollection.md">BeginFaceDataCollection</a></td>
<td align="left">Begins the collection of face data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder/Methods/CollectFaceDataAsync.md">CollectFaceDataAsync</a></td>
<td align="left">Collects face data asynchronously.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder/Methods/get_CaptureStatus_Method.md">get_CaptureStatus</a></td>
<td align="left">Gets the capture status of the face model builder.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder/Methods/get_CollectionStatus.md">get_CollectionStatus</a></td>
<td align="left">Gets the status of the face model builder collection.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder/Methods/GetCaptureStatusChangedE.md">GetCaptureStatusChangedEventData</a></td>
<td align="left">Gets data for the CaptureStatusChanged event.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder/Methods/GetCollectionStatusChang.md">GetCollectionStatusChangedEventData</a></td>
<td align="left">Gets data for the CollectionStatusChanged event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder/Methods/GetFaceData_Method.md">GetFaceData</a></td>
<td align="left">Gets the face model data.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder/Methods/SubscribeCaptureStatusCh.md">SubscribeCaptureStatusChanged</a></td>
<td align="left">Event handler to subscribe when the capture status changes.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder/Methods/SubscribeCollectionStatu.md">SubscribeCollectionStatusChanged</a></td>
<td align="left">Event handler to subscribe when the collection status changes.</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder/Methods/UnsubscribeCaptureStatus.md">UnsubscribeCaptureStatusChanged</a></td>
<td align="left">Unsubscribes an event handler from the CaptureStatusChanged event.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder/Methods/UnsubscribeCollectionSta.md">UnsubscribeCollectionStatusChanged</a></td>
<td align="left">Unsubscribes an event handler from the CollectionStatusChanged event.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IFaceModelBuilder Interface
RLTitle : IFaceModelBuilder Interface
KeywordK : IFaceModelBuilder interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IFaceModelBuilder
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder
KeywordA : T:Microsoft.Kinect.face.IFaceModelBuilder
AssetID : T:Microsoft.Kinect.face.IFaceModelBuilder
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
