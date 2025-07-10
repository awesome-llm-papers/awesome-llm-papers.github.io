---
layout: publication
title: 'Llm-blender: Ensembling Large Language Models With Pairwise Ranking And Generative
  Fusion'
authors: Dongfu Jiang, Xiang Ren, Bill Yuchen Lin
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
citations: 36
bibkey: jiang2023llm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.02561'}]
tags: [Model Architecture, Attention Mechanism, RAG, ACL, Tools, GPT, Evaluation,
  Merging]
---
We present LLM-Blender, an ensembling framework designed to attain
consistently superior performance by leveraging the diverse strengths of
multiple open-source large language models (LLMs). Our framework consists of
two modules: PairRanker and GenFuser, addressing the observation that optimal
LLMs for different examples can significantly vary. PairRanker employs a
specialized pairwise comparison method to distinguish subtle differences
between candidate outputs. It jointly encodes the input text and a pair of
candidates, using cross-attention encoders to determine the superior one. Our
results demonstrate that PairRanker exhibits the highest correlation with
ChatGPT-based ranking. Then, GenFuser aims to merge the top-ranked candidates,
generating an improved output by capitalizing on their strengths and mitigating
their weaknesses. To facilitate large-scale evaluation, we introduce a
benchmark dataset, MixInstruct, which is a mixture of multiple instruction
datasets featuring oracle pairwise comparisons. Our LLM-Blender significantly
outperform individual LLMs and baseline methods across various metrics,
establishing a substantial performance gap.