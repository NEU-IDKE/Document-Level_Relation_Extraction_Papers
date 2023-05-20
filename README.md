# Document-Level_Relation_Extraction_Papers
This is a repo listing some papers on Document-Level Relation Extraction published in recent years.

### Papers
1. **ATLOP**: **"Document-Level Relation Extraction with Adaptive Thresholding and Localized Context Pooling".**
*Wenxuan Zhou, Kevin Huang, Tengyu Ma, Jing Huang* (AAAI 2021)  \[[paper](https://www.aclweb.org/anthology/D18-1032)\]\[[code](https://github.com/1049451037/GCN-Align)\]

### Performance Evaluation

<h4>DocRED数据集测评结果:</h4>
<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;mso-yfti-tbllook:1184;mso-padding-alt:0cm 0cm 0cm 0cm'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=323 rowspan=2 style='width:242.45pt;border:solid windowtext 1.0pt;
  border-left:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US style='font-size:14.0pt'>Mode</span></b><span lang=EN-US
  style='font-size:14.0pt'>l</span></p>
  </td>
  <td width=389 colspan=4 valign=top style='width:291.45pt;border-top:solid windowtext 1.0pt;
  border-left:none;border-bottom:none;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US style='font-size:14.0pt'>Dev</span></b></p>
  </td>
  <td width=195 colspan=2 valign=top style='width:146.35pt;border:none;
  border-top:solid windowtext 1.0pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US style='font-size:14.0pt'>Test</span></b></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=102 valign=top style='width:76.6pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US>Intra-F1</span></b></p>
  </td>
  <td width=98 valign=top style='width:73.4pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US>Inter-F1</span></b></p>
  </td>
  <td width=93 valign=top style='width:70.05pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US>F1</span></b></p>
  </td>
  <td width=95 valign=top style='width:71.4pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><b><span
  lang=EN-US>lgn</span></b></span><b><span lang=EN-US> F1</span></b></p>
  </td>
  <td width=100 valign=top style='width:75.15pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><b><span
  lang=EN-US>F1</span></b></p>
  </td>
  <td width=95 valign=top style='width:71.2pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><b><span
  lang=EN-US>lgn</span></b></span><b><span lang=EN-US> F1</span></b></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=323 valign=top style='width:242.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>BERT-ATLOP<sub>BASE</sub></span><span
  style='font-size:9.0pt'>（<span lang=EN-US>Zhou at al.2021</span>）</span></p>
  </td>
  <td width=102 valign=top style='width:76.6pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'></td>
  <td width=98 valign=top style='width:73.4pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'></td>
  <td width=93 valign=top style='width:70.05pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>61.09+-0.16</span></p>
  </td>
  <td width=95 valign=top style='width:71.4pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>59.22+-0.15</span></p>
  </td>
  <td width=100 valign=top style='width:75.15pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>61.30</span></p>
  </td>
  <td width=95 valign=top style='width:71.2pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>59.31</span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3'>
  <td width=323 valign=top style='width:242.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US style='font-size:9.0pt'>RoBERTa</span></span><span lang=EN-US
  style='font-size:9.0pt'>-ATLOP<sub>LARGE</sub></span><span style='font-size:
  9.0pt'>（<span lang=EN-US>Zhou at al.2021</span>）<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
  <td width=102 valign=top style='width:76.6pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'></td>
  <td width=98 valign=top style='width:73.4pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'></td>
  <td width=93 valign=top style='width:70.05pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>63.18+-0.19<o:p></o:p></span></p>
  </td>
  <td width=95 valign=top style='width:71.4pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>61.32+-0.14<o:p></o:p></span></p>
  </td>
  <td width=100 valign=top style='width:75.15pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>63.40<o:p></o:p></span></p>
  </td>
  <td width=95 valign=top style='width:71.2pt;border:none;border-bottom:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-size:9.0pt'>61.39<o:p></o:p></span></p>
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

