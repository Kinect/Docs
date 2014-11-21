IVisualGestureBuilderDatabase::get\_AvailableGestures Method  
============================================================  

Gets a list of the available gestures in the database. <span id="syntaxSection"></span>

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
HRESULT get_AvailableGestures(  
         UINT32 capacity,  
         IGesture **availableGestures  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT32  
[in] The size of the array into which the list gestures will be copied.  

*availableGestures*    
Type: IGesture  
[out] The array into which list of gestures will be copied.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_AvailableGestures Method
RLTitle : IVisualGestureBuilderDatabase::get_AvailableGestures Method
KeywordK : get_AvailableGestures method
KeywordK : IVisualGestureBuilderDatabase::get_AvailableGestures method
KeywordF : IVisualGestureBuilderDatabase::get_AvailableGestures
KeywordF : get_AvailableGestures
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase.get_AvailableGestures(UINT32,IGesture@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase.get_AvailableGestures(UINT32,IGesture@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase.get_AvailableGestures(UINT32,IGesture@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase::get_AvailableGestures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
