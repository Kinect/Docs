HitTestResult Constructor  
=========================  

Initializes a new instance of the [HitTestResult](../HitTestResult_Class.md) class. <span id="syntaxSection"></span>

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
HitTestResult(  
         <a href="../PressableModel_Class.md">PressableModel</a>^ firstKinectAwareElement,  
         IVector&lt;<a href="../ManipulatableModel_Class.md">ManipulatableModel</a>&gt;^ manipulationAwareElements  
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
<td align="left"><pre><code>public HitTestResult (  
         <a href="../PressableModel_Class.md">PressableModel</a>firstKinectAwareElement,  
         IList&lt;<a href="../ManipulatableModel_Class.md">ManipulatableModel</a>&gt;manipulationAwareElements  
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
<td align="left"><pre><code>var hitTestResult = new Microsoft.Kinect.Toolkit.Input.HitTestResult(firstKinectAwareElement, manipulationAwareElements);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*firstKinectAwareElement*    
Type: [PressableModel](../PressableModel_Class.md)  
The first [PressableModel](../PressableModel_Class.md) object associated with a hit test.  

*manipulationAwareElements*    
[C++] Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[ManipulatableModel](../ManipulatableModel_Class.md)\>
  [C\#] Type: [IList](http://msdn.microsoft.com/en-us/library/5y536ey6.aspx)\<[ManipulatableModel](../ManipulatableModel_Class.md)\>
  [JavaScript] Type: [IVector](http://msdn.microsoft.com/en-us/library/br206631.aspx)\<[ManipulatableModel](../ManipulatableModel_Class.md)\>
   

The list of [ManipulatableModel](../ManipulatableModel_Class.md) objects associated with a hit test.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Toolkit.Input  
**Assembly:** (in )  

<span id="ID4ERB"></span>

See also  
========  

<span id="ID4ETB"></span>
#### Reference  

[HitTestResult Class](../HitTestResult_Class.md)  
 [Microsoft.Kinect.Toolkit.Input Namespace](../../Kinect.Toolkit.Input.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HitTestResult Constructor
RLTitle : HitTestResult Constructor
KeywordK : HitTestResult class, constructor
KeywordK : HitTestResult.HitTestResult constructor
KeywordF : Microsoft.Kinect.Toolkit.Input.HitTestResult.#ctor
KeywordF : Microsoft.Kinect.Toolkit.Input.HitTestResult.HitTestResult
KeywordF : Microsoft.Kinect.Toolkit.Input.HitTestResult.New
KeywordF : Microsoft.Kinect.Toolkit.Input.HitTestResult.#ctor(Microsoft.Kinect.Toolkit.Input.PressableModel,Windows.Foundation.Collections.IVector{Microsoft.Kinect.Toolkit.Input.ManipulatableModel})
KeywordF : HitTestResult.HitTestResult
KeywordF : HitTestResult.New
KeywordA : M:Microsoft.Kinect.Toolkit.Input.HitTestResult.#ctor(Microsoft.Kinect.Toolkit.Input.PressableModel,Windows.Foundation.Collections.IVector{Microsoft.Kinect.Toolkit.Input.ManipulatableModel})
AssetID : M:Microsoft.Kinect.Toolkit.Input.HitTestResult.#ctor(Microsoft.Kinect.Toolkit.Input.PressableModel,Windows.Foundation.Collections.IVector{Microsoft.Kinect.Toolkit.Input.ManipulatableModel})
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.Toolkit.Input.HitTestResult
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
