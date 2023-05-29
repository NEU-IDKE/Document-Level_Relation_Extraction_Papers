# Document-Level_Relation_Extraction_Papers
This is a repo listing some papers on Document-Level Relation Extraction published in recent years.

### Papers
1. **Eider**: **"Empowering Document-level Relation Extraction with Efficient Evidence Extraction and Inference-stage Fusion".**
*Yiqing Xie, Jiaming Shen, Sha Li, Yuning Mao, Jiawei Han* (ACL 2022)  \[[paper](https://arxiv.org/pdf/2106.08657v2.pdf)\]\[[code](https://github.com/veronicium/eider)\]
1. **SGR**: **"Document-level Relation Extraction via Subgraph Reasoning".**
*Xingyu Peng, Chong Zhang, Ke Xu* (IJCAI 2022)  \[[paper](https://www.ijcai.org/proceedings/2022/0601.pdf)\]\[[code](https://github.com/Crysta1ovo/SGR)\]
1. **ATLOP**: **"Document-Level Relation Extraction with Adaptive Thresholding and Localized Context Pooling".**
*Wenxuan Zhou, Kevin Huang, Tengyu Ma, Jing Huang* (AAAI 2021)  \[[paper](https://arxiv.org/pdf/2010.11304.pdf)\]\[[code](https://github.com/wzhouad/ATLOP)\]

### Performance Evaluation

<h4>DocRED数据集测评结果:</h4>
<table width=1000px>

 <tr>
  <td width=400 rowspan=2>
  <p align=center style='text-align:center'><b><span lang=EN-US style='font-size:14.0pt'>Model</span></b></p>
  </td>

  <td width=400 colspan=4>
  <p align=center style='text-align:center'><b><span lang=EN-US style='font-size:14.0pt'>Dev</span></b></p>
  </td>

  <td width=200 colspan=2>
  <p align=center style='text-align:center'><b><span lang=EN-US style='font-size:14.0pt'>F1</span></b></p>
  </td>
 </tr>

 <tr>
  <td width=100 >
  <p  align=center style='text-align:center'><b><span lang=EN-US>Intra-F1</span></b></p>
  </td>
  <td width=100>
  <p  align=center style='text-align:center'><b><span lang=EN-US>Inter-F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>lgn F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>lgn F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>F1</span></b></p>
  </td>
 </tr>

  <tr>
  <td width=400 align=center style='text-align:center'>
  <p ><span lang=EN-US style='font-size:9.0pt'>BERT-ATLOP<sub>BASE</sub></span><span style='font-size:9.0pt'>（<span lang=EN-US>Zhou et al. 2021</span>）</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US></span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US></span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>59.22±0.15</span></p>
  </td>
  <td width=100>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>61.09±0.16</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>59.31</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>61.30</span></p>
  </td>
 </tr>
 <tr>
  <td width=400 align=center style='text-align:center'>
  <p ><span lang=EN-US style='font-size:9.0pt'>EIDER-BERT<sub>BASE</sub></span><span style='font-size:9.0pt'>（<span lang=EN-US>Xie et al. 2022</span>）</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US>68.47±0.08</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US>55.21±0.21</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>60.51±0.11</span></p>
  </td>
  <td width=100>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>62.48±0.13</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>60.42</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>62.47</span></p>
  </td>
 </tr>
 
  <tr>
  <td width=400 align=center style='text-align:center'>
  <p ><span lang=EN-US style='font-size:9.0pt'>SGR<sub>lstm</sub></span><span style='font-size:9.0pt'>（<span lang=EN-US>Peng et al. 2022</span>）</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US>63.58</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US>49.94</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>55.82</span></p>
  </td>
  <td width=100>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>57.49</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>55.12</span></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><span lang=EN-US style='font-size:9.0pt'>57.15</span></p>
  </td>
 </tr>
 

</table>

<h4>Re-DocRED数据集测评结果:</h4>
<table width=1000px>

 <tr>
  <td width=400 rowspan=2>
  <p align=center style='text-align:center'><b><span lang=EN-US style='font-size:14.0pt'>Model</span></b></p>
  </td>

  <td width=400 colspan=4>
  <p align=center style='text-align:center'><b><span lang=EN-US style='font-size:14.0pt'>Dev</span></b></p>
  </td>

  <td width=200 colspan=2>
  <p align=center style='text-align:center'><b><span lang=EN-US style='font-size:14.0pt'>F1</span></b></p>
  </td>
 </tr>

 <tr>
  <td width=100 >
  <p  align=center style='text-align:center'><b><span lang=EN-US>Intra-F1</span></b></p>
  </td>
  <td width=100>
  <p  align=center style='text-align:center'><b><span lang=EN-US>Inter-F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>lgn F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>lgn F1</span></b></p>
  </td>
  <td width=100>
  <p align=center style='text-align:center'><b><span lang=EN-US>F1</span></b></p>
  </td>
 </tr>

</table>

