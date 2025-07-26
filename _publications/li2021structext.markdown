---
layout: publication
title: 'Structext: Structured Text Understanding With Multi-modal Transformers'
authors: Yulin Li, Yuxi Qian, Yuchen Yu, Xiameng Qin, Chengquan Zhang, Yan Liu, Kun
  Yao, Junyu Han, Jingtuo Liu, Errui Ding
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2021
bibkey: li2021structext
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.02923'}]
tags: ["Model Architecture"]
short_authors: Li et al.
---
Structured text understanding on Visually Rich Documents (VRDs) is a crucial
part of Document Intelligence. Due to the complexity of content and layout in
VRDs, structured text understanding has been a challenging task. Most existing
studies decoupled this problem into two sub-tasks: entity labeling and entity
linking, which require an entire understanding of the context of documents at
both token and segment levels. However, little work has been concerned with the
solutions that efficiently extract the structured data from different levels.
This paper proposes a unified framework named StrucTexT, which is flexible and
effective for handling both sub-tasks. Specifically, based on the transformer,
we introduce a segment-token aligned encoder to deal with the entity labeling
and entity linking tasks at different levels of granularity. Moreover, we
design a novel pre-training strategy with three self-supervised tasks to learn
a richer representation. StrucTexT uses the existing Masked Visual Language
Modeling task and the new Sentence Length Prediction and Paired Boxes Direction
tasks to incorporate the multi-modal information across text, image, and
layout. We evaluate our method for structured text understanding at
segment-level and token-level and show it outperforms the state-of-the-art
counterparts with significantly superior performance on the FUNSD, SROIE, and
EPHOIE datasets.