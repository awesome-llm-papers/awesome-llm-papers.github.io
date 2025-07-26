---
layout: publication
title: 'Gpt-too: A Language-model-first Approach For Amr-to-text Generation'
authors: Manuel Mager, Ramon Fernandez Astudillo, Tahira Naseem, Md Arafat Sultan,
  Young-suk Lee, Radu Florian, Salim Roukos
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: mager2020gpt
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.09123'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Mager et al.
---
Meaning Representations (AMRs) are broad-coverage sentence-level semantic
graphs. Existing approaches to generating text from AMR have focused on
training sequence-to-sequence or graph-to-sequence models on AMR annotated data
only. In this paper, we propose an alternative approach that combines a strong
pre-trained language model with cycle consistency-based re-scoring. Despite the
simplicity of the approach, our experimental results show these models
outperform all previous techniques on the English LDC2017T10dataset, including
the recent use of transformer architectures. In addition to the standard
evaluation metrics, we provide human evaluation experiments that further
substantiate the strength of our approach.