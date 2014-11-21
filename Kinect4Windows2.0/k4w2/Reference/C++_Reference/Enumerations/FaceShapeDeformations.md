FaceShapeDeformations Enumeration  
=================================  

<span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FaceShapeDeformations  
{  
    FaceShapeDeformations_PCA01 = 0,  
    FaceShapeDeformations_PCA02 = 1,  
    FaceShapeDeformations_PCA03 = 2,  
    FaceShapeDeformations_PCA04 = 3,  
    FaceShapeDeformations_PCA05 = 4,  
    FaceShapeDeformations_PCA06 = 5,  
    FaceShapeDeformations_PCA07 = 6,  
    FaceShapeDeformations_PCA08 = 7,  
    FaceShapeDeformations_PCA09 = 8,  
    FaceShapeDeformations_PCA10 = 9,  
    FaceShapeDeformations_Chin03 = 10,  
    FaceShapeDeformations_Forehead00 = 11,  
    FaceShapeDeformations_Cheeks02 = 12,  
    FaceShapeDeformations_Cheeks01 = 13,  
    FaceShapeDeformations_MouthBag01 = 14,  
    FaceShapeDeformations_MouthBag02 = 15,  
    FaceShapeDeformations_Eyes02 = 16,  
    FaceShapeDeformations_MouthBag03 = 17,  
    FaceShapeDeformations_Forehead04 = 18,  
    FaceShapeDeformations_Nose00 = 19,  
    FaceShapeDeformations_Nose01 = 20,  
    FaceShapeDeformations_Nose02 = 21,  
    FaceShapeDeformations_MouthBag06 = 22,  
    FaceShapeDeformations_MouthBag05 = 23,  
    FaceShapeDeformations_Cheeks00 = 24,  
    FaceShapeDeformations_Mask03 = 25,  
    FaceShapeDeformations_Eyes03 = 26,  
    FaceShapeDeformations_Nose03 = 27,  
    FaceShapeDeformations_Eyes08 = 28,  
    FaceShapeDeformations_MouthBag07 = 29,  
    FaceShapeDeformations_Eyes00 = 30,  
    FaceShapeDeformations_Nose04 = 31,  
    FaceShapeDeformations_Mask04 = 32,  
    FaceShapeDeformations_Chin04 = 33,  
    FaceShapeDeformations_Forehead05 = 34,  
    FaceShapeDeformations_Eyes06 = 35,  
    FaceShapeDeformations_Eyes11 = 36,  
    FaceShapeDeformations_Nose05 = 37,  
    FaceShapeDeformations_Mouth07 = 38,  
    FaceShapeDeformations_Cheeks08 = 39,  
    FaceShapeDeformations_Eyes09 = 40,  
    FaceShapeDeformations_Mask10 = 41,  
    FaceShapeDeformations_Mouth09 = 42,  
    FaceShapeDeformations_Nose07 = 43,  
    FaceShapeDeformations_Nose08 = 44,  
    FaceShapeDeformations_Cheeks07 = 45,  
    FaceShapeDeformations_Mask07 = 46,  
    FaceShapeDeformations_MouthBag09 = 47,  
    FaceShapeDeformations_Nose06 = 48,  
    FaceShapeDeformations_Chin02 = 49,  
    FaceShapeDeformations_Eyes07 = 50,  
    FaceShapeDeformations_Cheeks10 = 51,  
    FaceShapeDeformations_Rim20 = 52,  
    FaceShapeDeformations_Mask22 = 53,  
    FaceShapeDeformations_MouthBag15 = 54,  
    FaceShapeDeformations_Chin01 = 55,  
    FaceShapeDeformations_Cheeks04 = 56,  
    FaceShapeDeformations_Eyes17 = 57,  
    FaceShapeDeformations_Cheeks13 = 58,  
    FaceShapeDeformations_Mouth02 = 59,  
    FaceShapeDeformations_MouthBag12 = 60,  
    FaceShapeDeformations_Mask19 = 61,  
    FaceShapeDeformations_Mask20 = 62,  
    FaceShapeDeformations_Forehead06 = 63,  
    FaceShapeDeformations_Mouth13 = 64,  
    FaceShapeDeformations_Mask25 = 65,  
    FaceShapeDeformations_Chin05 = 66,  
    FaceShapeDeformations_Cheeks20 = 67,  
    FaceShapeDeformations_Nose09 = 68,  
    FaceShapeDeformations_Nose10 = 69,  
    FaceShapeDeformations_MouthBag27 = 70,  
    FaceShapeDeformations_Mouth11 = 71,  
    FaceShapeDeformations_Cheeks14 = 72,  
    FaceShapeDeformations_Eyes16 = 73,  
    FaceShapeDeformations_Mask29 = 74,  
    FaceShapeDeformations_Nose15 = 75,  
    FaceShapeDeformations_Cheeks11 = 76,  
    FaceShapeDeformations_Mouth16 = 77,  
    FaceShapeDeformations_Eyes19 = 78,  
    FaceShapeDeformations_Mouth17 = 79,  
    FaceShapeDeformations_MouthBag36 = 80,  
    FaceShapeDeformations_Mouth15 = 81,  
    FaceShapeDeformations_Cheeks25 = 82,  
    FaceShapeDeformations_Cheeks16 = 83,  
    FaceShapeDeformations_Cheeks18 = 84,  
    FaceShapeDeformations_Rim07 = 85,  
    FaceShapeDeformations_Nose13 = 86,  
    FaceShapeDeformations_Mouth18 = 87,  
    FaceShapeDeformations_Cheeks19 = 88,  
    FaceShapeDeformations_Rim21 = 89,  
    FaceShapeDeformations_Mouth22 = 90,  
    FaceShapeDeformations_Nose18 = 91,  
    FaceShapeDeformations_Nose16 = 92,  
    FaceShapeDeformations_Rim22 = 93,  
    FaceShapeDeformations_Count = (FaceShapeDeformations_Rim22+1)  
} FaceShapeDeformations, FaceShapeDeformations_PCA01, FaceShapeDeformations_PCA02, FaceShapeDeformations_PCA03, FaceShapeDeformations_PCA04, FaceShapeDeformations_PCA05, FaceShapeDeformations_PCA06, FaceShapeDeformations_PCA07, FaceShapeDeformations_PCA08, FaceShapeDeformations_PCA09, FaceShapeDeformations_PCA10, FaceShapeDeformations_Chin03, FaceShapeDeformations_Forehead00, FaceShapeDeformations_Cheeks02, FaceShapeDeformations_Cheeks01, FaceShapeDeformations_MouthBag01, FaceShapeDeformations_MouthBag02, FaceShapeDeformations_Eyes02, FaceShapeDeformations_MouthBag03, FaceShapeDeformations_Forehead04, FaceShapeDeformations_Nose00, FaceShapeDeformations_Nose01, FaceShapeDeformations_Nose02, FaceShapeDeformations_MouthBag06, FaceShapeDeformations_MouthBag05, FaceShapeDeformations_Cheeks00, FaceShapeDeformations_Mask03, FaceShapeDeformations_Eyes03, FaceShapeDeformations_Nose03, FaceShapeDeformations_Eyes08, FaceShapeDeformations_MouthBag07, FaceShapeDeformations_Eyes00, FaceShapeDeformations_Nose04, FaceShapeDeformations_Mask04, FaceShapeDeformations_Chin04, FaceShapeDeformations_Forehead05, FaceShapeDeformations_Eyes06, FaceShapeDeformations_Eyes11, FaceShapeDeformations_Nose05, FaceShapeDeformations_Mouth07, FaceShapeDeformations_Cheeks08, FaceShapeDeformations_Eyes09, FaceShapeDeformations_Mask10, FaceShapeDeformations_Mouth09, FaceShapeDeformations_Nose07, FaceShapeDeformations_Nose08, FaceShapeDeformations_Cheeks07, FaceShapeDeformations_Mask07, FaceShapeDeformations_MouthBag09, FaceShapeDeformations_Nose06, FaceShapeDeformations_Chin02, FaceShapeDeformations_Eyes07, FaceShapeDeformations_Cheeks10, FaceShapeDeformations_Rim20, FaceShapeDeformations_Mask22, FaceShapeDeformations_MouthBag15, FaceShapeDeformations_Chin01, FaceShapeDeformations_Cheeks04, FaceShapeDeformations_Eyes17, FaceShapeDeformations_Cheeks13, FaceShapeDeformations_Mouth02, FaceShapeDeformations_MouthBag12, FaceShapeDeformations_Mask19, FaceShapeDeformations_Mask20, FaceShapeDeformations_Forehead06, FaceShapeDeformations_Mouth13, FaceShapeDeformations_Mask25, FaceShapeDeformations_Chin05, FaceShapeDeformations_Cheeks20, FaceShapeDeformations_Nose09, FaceShapeDeformations_Nose10, FaceShapeDeformations_MouthBag27, FaceShapeDeformations_Mouth11, FaceShapeDeformations_Cheeks14, FaceShapeDeformations_Eyes16, FaceShapeDeformations_Mask29, FaceShapeDeformations_Nose15, FaceShapeDeformations_Cheeks11, FaceShapeDeformations_Mouth16, FaceShapeDeformations_Eyes19, FaceShapeDeformations_Mouth17, FaceShapeDeformations_MouthBag36, FaceShapeDeformations_Mouth15, FaceShapeDeformations_Cheeks25, FaceShapeDeformations_Cheeks16, FaceShapeDeformations_Cheeks18, FaceShapeDeformations_Rim07, FaceShapeDeformations_Nose13, FaceShapeDeformations_Mouth18, FaceShapeDeformations_Cheeks19, FaceShapeDeformations_Rim21, FaceShapeDeformations_Mouth22, FaceShapeDeformations_Nose18, FaceShapeDeformations_Nose16, FaceShapeDeformations_Rim22, FaceShapeDeformations_Count;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EQEAC"></span>

Constants  
=========  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Constant</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">FaceShapeDeformations_PCA01</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_PCA02</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_PCA03</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_PCA04</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_PCA05</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_PCA06</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_PCA07</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_PCA08</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_PCA09</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_PCA10</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Chin03</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Forehead00</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks02</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Cheeks01</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_MouthBag01</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_MouthBag02</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes02</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_MouthBag03</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Forehead04</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose00</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Nose01</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose02</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_MouthBag06</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_MouthBag05</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks00</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mask03</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes03</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose03</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes08</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_MouthBag07</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes00</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose04</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mask04</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Chin04</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Forehead05</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Eyes06</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes11</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose05</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mouth07</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Cheeks08</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes09</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mask10</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mouth09</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose07</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Nose08</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Cheeks07</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mask07</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_MouthBag09</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Nose06</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Chin02</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes07</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Cheeks10</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Rim20</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mask22</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_MouthBag15</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Chin01</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks04</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Eyes17</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks13</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mouth02</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_MouthBag12</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mask19</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mask20</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Forehead06</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mouth13</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mask25</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Chin05</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Cheeks20</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Nose09</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose10</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_MouthBag27</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mouth11</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks14</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Eyes16</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mask29</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose15</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks11</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mouth16</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Eyes19</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mouth17</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_MouthBag36</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mouth15</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks25</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Cheeks16</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks18</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Rim07</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Nose13</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Mouth18</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Cheeks19</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Rim21</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Mouth22</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Nose18</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Nose16</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">FaceShapeDeformations_Rim22</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">FaceShapeDeformations_Count</td>
<td align="left"></td>
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
TOCTitle : FaceShapeDeformations Enumeration
RLTitle : FaceShapeDeformations Enumeration
KeywordK : FaceShapeDeformations enumeration
HelpPriority : 2
KeywordF : FaceShapeDeformations
KeywordF : Microsoft.Kinect.face.FaceShapeDeformations
KeywordA : T:Microsoft.Kinect.face.FaceShapeDeformations
AssetID : T:Microsoft.Kinect.face.FaceShapeDeformations
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FaceShapeDeformations
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
