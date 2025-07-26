---
layout: publication
title: Editing-based SQL Query Generation For Cross-domain Context-dependent Questions
authors: Rui Zhang, Tao Yu, He Yang Er, Sungrok Shim, Eric Xue, Xi Victoria Lin, Tianze
  Shi, Caiming Xiong, Richard Socher, Dragomir Radev
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: zhang2019editing
citations: 114
additional_links: [{name: Code, url: 'https://github.com/ryanzhumich/sparc_atis_pytorch'},
  {name: Paper, url: 'https://arxiv.org/abs/1909.00786'}]
tags: ["Datasets", "EMNLP"]
short_authors: Zhang et al.
---
We focus on the cross-domain context-dependent text-to-SQL generation task.
Based on the observation that adjacent natural language questions are often
linguistically dependent and their corresponding SQL queries tend to overlap,
we utilize the interaction history by editing the previous predicted query to
improve the generation quality. Our editing mechanism views SQL as sequences
and reuses generation results at the token level in a simple manner. It is
flexible to change individual tokens and robust to error propagation.
Furthermore, to deal with complex table structures in different domains, we
employ an utterance-table encoder and a table-aware decoder to incorporate the
context of the user utterance and the table schema. We evaluate our approach on
the SParC dataset and demonstrate the benefit of editing compared with the
state-of-the-art baselines which generate SQL from scratch. Our code is
available at https://github.com/ryanzhumich/sparc_atis_pytorch.