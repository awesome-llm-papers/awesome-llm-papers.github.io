---
layout: publication
title: 'ERNIE-M: Enhanced Multilingual Representation By Aligning Cross-lingual Semantics
  With Monolingual Corpora'
authors: Xuan Ouyang, Shuohuan Wang, Chao Pang, Yu Sun, Hao Tian, Hua Wu, Haifeng
  Wang
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: ouyang2020ernie
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15674'}]
tags: ["EMNLP"]
short_authors: Ouyang et al.
---
Recent studies have demonstrated that pre-trained cross-lingual models
achieve impressive performance in downstream cross-lingual tasks. This
improvement benefits from learning a large amount of monolingual and parallel
corpora. Although it is generally acknowledged that parallel corpora are
critical for improving the model performance, existing methods are often
constrained by the size of parallel corpora, especially for low-resource
languages. In this paper, we propose ERNIE-M, a new training method that
encourages the model to align the representation of multiple languages with
monolingual corpora, to overcome the constraint that the parallel corpus size
places on the model performance. Our key insight is to integrate
back-translation into the pre-training process. We generate pseudo-parallel
sentence pairs on a monolingual corpus to enable the learning of semantic
alignments between different languages, thereby enhancing the semantic modeling
of cross-lingual models. Experimental results show that ERNIE-M outperforms
existing cross-lingual models and delivers new state-of-the-art results in
various cross-lingual downstream tasks.