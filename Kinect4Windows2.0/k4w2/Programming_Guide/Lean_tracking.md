Lean tracking  
=============  

Lean tracking APIs make it possible to incorporate player lean, how much their body is leaning from vertical, into their experience. You might use this feature to have a player lean around an obstacle to see something for instance. The value returned is pre-filtered for an optimum combination of stability and latency and is packaged to resemble the thumbstick API.  

Leaning left and right corresponds to X movement; leaning forward and back corresponds to Y movement. The values range between -1 and 1 in both directions, where 1 roughly corresponds to 45 degrees of lean.  

Access the lean values from the body frame.  

<span id="ID4EQ"></span>

Get the X and Y lean values from the body frame  
===============================================  

This code gets the X and Y lean values from the body frame.  

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
<td align="left"><pre><code>
IBody^ body = // Gets the body frame using NUI APIs.  

Windows::Foundation::Point leanAmount = body-&gt;Lean;  
float x = leanAmount.X;  
float y = leanAmount.Y;  

if(body-&gt;LeanTrackingState == TrackingState::Tracked)  
{  
  // Do stuff with lean values.  
}  
else  
{  
  // Use values from previous frame or default values.  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E1"></span>

See also  
========  

[Body tracking](Body_tracking.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Lean tracking
RLTitle : Lean tracking
KeywordA : O:Microsoft.Kinect.k4w_nui_lean_tracking
KeywordA : e19ad7ee-bac5-3277-3092-92a3efb2842d
KeywordK : Lean tracking
AssetID : e19ad7ee-bac5-3277-3092-92a3efb2842d
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
