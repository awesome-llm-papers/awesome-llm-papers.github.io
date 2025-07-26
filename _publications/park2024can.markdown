---
layout: publication
title: Can Mamba Learn How To Learn? A Comparative Study On In-context Learning Tasks
authors: Jongho Park, Jaeseung Park, Zheyang Xiong, Nayoung Lee, Jaewoong Cho, Samet
  Oymak, Kangwook Lee, Dimitris Papailiopoulos
conference: No Venue
year: 2024
bibkey: park2024can
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.04248'}]
tags: ["In Context Learning"]
short_authors: Park et al.
---
State-space models (SSMs), such as Mamba Gu & Dao (2034), have been proposed as alternatives to Transformer networks in language modeling, by incorporating gating, convolutions, and input-dependent token selection to mitigate the quadratic cost of multi-head attention. Although SSMs exhibit competitive performance, their in-context learning (ICL) capabilities, a remarkable emergent property of modern language models that enables task execution without parameter optimization, remain underexplored compared to Transformers. In this study, we evaluate the ICL performance of SSMs, focusing on Mamba, against Transformer models across various tasks. Our results show that SSMs perform comparably to Transformers in standard regression ICL tasks, while outperforming them in tasks like sparse parity learning. However, SSMs fall short in tasks involving non-standard retrieval functionality. To address these limitations, we introduce a hybrid model, \variant, that combines Mamba with attention blocks, surpassing individual models in tasks where they struggle independently. Our findings suggest that hybrid architectures offer promising avenues for enhancing ICL in language models.

https://huggingface.co/discussions/paper/65c2f90b82e4546db95c2704