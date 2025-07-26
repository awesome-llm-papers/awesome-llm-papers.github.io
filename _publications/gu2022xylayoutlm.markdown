---
layout: publication
title: 'Xylayoutlm: Towards Layout-aware Multimodal Networks For Visually-rich Document
  Understanding'
authors: Zhangxuan Gu, Changhua Meng, Ke Wang, Jun Lan, Weiqiang Wang, Ming Gu, Liqing
  Zhang
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: gu2022xylayoutlm
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.06947'}]
tags: ["CVPR"]
short_authors: Gu et al.
---
Recently, various multimodal networks for Visually-Rich Document
Understanding(VRDU) have been proposed, showing the promotion of transformers
by integrating visual and layout information with the text embeddings. However,
most existing approaches utilize the position embeddings to incorporate the
sequence information, neglecting the noisy improper reading order obtained by
OCR tools. In this paper, we propose a robust layout-aware multimodal network
named XYLayoutLM to capture and leverage rich layout information from proper
reading orders produced by our Augmented XY Cut. Moreover, a Dilated
Conditional Position Encoding module is proposed to deal with the input
sequence of variable lengths, and it additionally extracts local layout
information from both textual and visual modalities while generating position
embeddings. Experiment results show that our XYLayoutLM achieves competitive
results on document understanding tasks.