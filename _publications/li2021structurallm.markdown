---
layout: publication
title: 'Structurallm: Structural Pre-training For Form Understanding'
authors: Chenliang Li, Bin Bi, Ming Yan, Wei Wang, Songfang Huang, Fei Huang, Luo
  Si
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: li2021structurallm
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.11210'}]
tags: ["Training Techniques"]
short_authors: Li et al.
---
Large pre-trained language models achieve state-of-the-art results when
fine-tuned on downstream NLP tasks. However, they almost exclusively focus on
text-only representation, while neglecting cell-level layout information that
is important for form image understanding. In this paper, we propose a new
pre-training approach, StructuralLM, to jointly leverage cell and layout
information from scanned documents. Specifically, we pre-train StructuralLM
with two new designs to make the most of the interactions of cell and layout
information: 1) each cell as a semantic unit; 2) classification of cell
positions. The pre-trained StructuralLM achieves new state-of-the-art results
in different types of downstream tasks, including form understanding (from
78.95 to 85.14), document visual question answering (from 72.59 to 83.94) and
document image classification (from 94.43 to 96.08).