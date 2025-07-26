---
layout: publication
title: Multi-step Reasoning Via Recurrent Dual Attention For Visual Dialog
authors: Zhe Gan, Yu Cheng, Ahmed El Kholy, Linjie Li, Jingjing Liu, Jianfeng Gao
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: gan2019multi
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.00579'}]
tags: ["Datasets"]
short_authors: Gan et al.
---
This paper presents a new model for visual dialog, Recurrent Dual Attention
Network (ReDAN), using multi-step reasoning to answer a series of questions
about an image. In each question-answering turn of a dialog, ReDAN infers the
answer progressively through multiple reasoning steps. In each step of the
reasoning process, the semantic representation of the question is updated based
on the image and the previous dialog history, and the recurrently-refined
representation is used for further reasoning in the subsequent step. On the
VisDial v1.0 dataset, the proposed ReDAN model achieves a new state-of-the-art
of 64.47% NDCG score. Visualization on the reasoning process further
demonstrates that ReDAN can locate context-relevant visual and textual clues
via iterative refinement, which can lead to the correct answer step-by-step.