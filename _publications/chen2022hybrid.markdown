---
layout: publication
title: Hybrid Transformer With Multi-level Fusion For Multimodal Knowledge Graph Completion
authors: Xiang Chen, Ningyu Zhang, Lei Li, Shumin Deng, Chuanqi Tan, Changliang Xu,
  Fei Huang, Luo Si, Huajun Chen
conference: Proceedings of the 45th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2022
bibkey: chen2022hybrid
citations: 113
additional_links: [{name: Code, url: 'https://github.com/zjunlp/MKGformer'}, {name: Paper,
    url: 'https://arxiv.org/abs/2205.02357'}]
tags: ["Model Architecture", "SIGIR"]
short_authors: Chen et al.
---
Multimodal Knowledge Graphs (MKGs), which organize visual-text factual
knowledge, have recently been successfully applied to tasks such as information
retrieval, question answering, and recommendation system. Since most MKGs are
far from complete, extensive knowledge graph completion studies have been
proposed focusing on the multimodal entity, relation extraction and link
prediction. However, different tasks and modalities require changes to the
model architecture, and not all images/objects are relevant to text input,
which hinders the applicability to diverse real-world scenarios. In this paper,
we propose a hybrid transformer with multi-level fusion to address those
issues. Specifically, we leverage a hybrid transformer architecture with
unified input-output for diverse multimodal knowledge graph completion tasks.
Moreover, we propose multi-level fusion, which integrates visual and text
representation via coarse-grained prefix-guided interaction and fine-grained
correlation-aware fusion modules. We conduct extensive experiments to validate
that our MKGformer can obtain SOTA performance on four datasets of multimodal
link prediction, multimodal RE, and multimodal NER. Code is available in
https://github.com/zjunlp/MKGformer.