# Document-Level_Relation_Extraction_Papers
This is a repo listing some papers on Document-Level Relation Extraction published in recent years.

### Papers
1. **ATLOP**: **"Document-Level Relation Extraction with Adaptive Thresholding and Localized Context Pooling".**
*Wenxuan Zhou, Kevin Huang, Tengyu Ma, Jing Huang* (AAAI 2021)  \[[paper](https://arxiv.org/pdf/2010.11304.pdf)\]\[[code](https://github.com/wzhouad/ATLOP)\]

### Performance Evaluation

<h4>DocRED数据集测评结果:</h4>
    <tablewidth=1000px>
    <tr>
    <tdwidth=400rowspan=2>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-USstyle='font-size:14.0pt'>Model</span></b></p>
    </td>
    <tdwidth=400colspan=4>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-USstyle='font-size:14.0pt'>Dev</span></b></p>
    </td>
    <tdwidth=200colspan=2>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-USstyle='font-size:14.0pt'>F1</span></b></p>
    </td>
    </tr>
    <tr>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-US>Intra-F1</span></b></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-US>Inter-F1</span></b></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-US>lgnF1</span></b></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-US>F1</span></b></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-US>lgnF1</span></b></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><b><span
    lang=EN-US>F1</span></b></p>
    </td>
    </tr>
    <tr>
    <tdwidth=400>
    <palign=centerstyle='text-align:center'><spanlang=EN-US
    style='font-size:9.0pt'>BERT-ATLOP<sub>BASE</sub></span><span
    style='font-size:9.0pt'>（<spanlang=EN-US>Zhouatal.2021</span>）</span></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><spanlang=EN-US></span></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><spanlang=EN-US></span></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><spanlang=EN-US
    style='font-size:9.0pt'>59.22+-0.15</span></p>
    </td>
    <tdwidth=100>
    <pclass=MsoNormalalign=centerstyle='text-align:center'><spanlang=EN-US
    style='font-size:9.0pt'>61.09+-0.16</span>
    </p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><spanlang=EN-US
    style='font-size:9.0pt'>59.31</span></p>
    </td>
    <tdwidth=100>
    <palign=centerstyle='text-align:center'><spanlang=EN-US
    style='font-size:9.0pt'>61.30</span></p>
    </td>
    </tr>
    </table>

<h4>Re-DocRED数据集测评结果:</h4>
<table border="1" width="500px" cellspacing="10">
<tr>
  <th align="left">Model</th>
  <th align="center">Dev</th>
  <th align="center">Test</th>
</tr>
<tr>
  <td>行1，列1</td>
  <td>行1，列2</td>
  <td>行1，列3</td>
</tr>
<tr>
  <td colspan="2" align="center">合并行单元格</td>
  <td>行2，列3</td>
</tr>
<tr>
  <td rowspan="2" align="center">合并列单元格</td>
  <td>行3，列2</td>
  <td>行3，列3</td>
</tr>
<tr>
  <td>行4，列2</th>
  <td>行4，列3</td>
</tr>
</table>

