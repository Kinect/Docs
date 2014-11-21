IKinectCoreWindow Interface  
===========================  

Represents a Kinect for Windows app with input events and basic user interface behaviors. Only 1 core window is in “focus” at any one time, and that one gets the pointers and related events. he coordinate space of the window is normalized to the [0,1] range in both dimensions. <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IKinectCoreWindow : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectCoreWindow** has the following members.  

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
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/GetPointerEnteredEventData.md">GetPointerEnteredEventData</a></td>
<td align="left">Gets the event data when a the pointer entered.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/GetPointerExitedEventData.md">GetPointerExitedEventData</a></td>
<td align="left">Gets the event data when a the pointer exited.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/GetPointerMovedEventData.md">GetPointerMovedEventData</a></td>
<td align="left">Gets the event data when a the pointer moved.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/SubscribePointerEntered.md">SubscribePointerEntered</a></td>
<td align="left">Subscribes to the specified event handler to handle pointer exited events.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/SubscribePointerExited.md">SubscribePointerExited</a></td>
<td align="left">Subscribes to the specified event handler to handle pointer exited events.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/SubscribePointerMoved_Method.md">SubscribePointerMoved</a></td>
<td align="left">Subscribes to the specified event handler to handle pointer moved events.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/UnsubscribePointerEntered.md">UnsubscribePointerEntered</a></td>
<td align="left">Unsubscribes the specified event handler that processes pointer entered events.</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/UnsubscribePointerExited.md">UnsubscribePointerExited</a></td>
<td align="left">Unsubscribes the specified event handler that processes pointer exited events.</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectCoreWindow_Interface/Methods/UnsubscribePointerMoved.md">UnsubscribePointerMoved</a></td>
<td align="left">Unsubscribes the specified event handler that processes pointer moved events.</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IKinectCoreWindow Interface
RLTitle : IKinectCoreWindow Interface
KeywordK : IKinectCoreWindow interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectCoreWindow
KeywordF : Microsoft.Kinect.kinect.IKinectCoreWindow
KeywordA : T:Microsoft.Kinect.kinect.IKinectCoreWindow
AssetID : T:Microsoft.Kinect.kinect.IKinectCoreWindow
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectCoreWindow
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
