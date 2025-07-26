---
layout: publication
title: Dual Attention Networks For Visual Reference Resolution In Visual Dialog
authors: Gi-cheon Kang, Jaeseo Lim, Byoung-tak Zhang
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: kang2019dual
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.09368'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Gi-cheon Kang, Jaeseo Lim, Byoung-tak Zhang
---
Visual dialog (VisDial) is a task which requires an AI agent to answer a
series of questions grounded in an image. Unlike in visual question answering
(VQA), the series of questions should be able to capture a temporal context
from a dialog history and exploit visually-grounded information. A problem
called visual reference resolution involves these challenges, requiring the
agent to resolve ambiguous references in a given question and find the
references in a given image. In this paper, we propose Dual Attention Networks
(DAN) for visual reference resolution. DAN consists of two kinds of attention
networks, REFER and FIND. Specifically, REFER module learns latent
relationships between a given question and a dialog history by employing a
self-attention mechanism. FIND module takes image features and reference-aware
representations (i.e., the output of REFER module) as input, and performs
visual grounding via bottom-up attention mechanism. We qualitatively and
quantitatively evaluate our model on VisDial v1.0 and v0.9 datasets, showing
that DAN outperforms the previous state-of-the-art model by a significant
margin.