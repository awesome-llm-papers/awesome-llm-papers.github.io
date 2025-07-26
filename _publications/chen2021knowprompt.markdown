---
layout: publication
title: 'Knowprompt: Knowledge-aware Prompt-tuning With Synergistic Optimization For
  Relation Extraction'
authors: Xiang Chen, Ningyu Zhang, Xin Xie, Shumin Deng, Yunzhi Yao, Chuanqi Tan,
  Fei Huang, Luo Si, Huajun Chen
conference: Proceedings of the ACM Web Conference 2022
year: 2022
bibkey: chen2021knowprompt
citations: 292
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.07650'}]
tags: ["Few-Shot", "Has Code", "Prompting"]
short_authors: Chen et al.
---
Recently, prompt-tuning has achieved promising results for specific few-shot
classification tasks. The core idea of prompt-tuning is to insert text pieces
(i.e., templates) into the input and transform a classification task into a
masked language modeling problem. However, for relation extraction, determining
an appropriate prompt template requires domain expertise, and it is cumbersome
and time-consuming to obtain a suitable label word. Furthermore, there exists
abundant semantic and prior knowledge among the relation labels that cannot be
ignored. To this end, we focus on incorporating knowledge among relation labels
into prompt-tuning for relation extraction and propose a Knowledge-aware
Prompt-tuning approach with synergistic optimization (KnowPrompt).
Specifically, we inject latent knowledge contained in relation labels into
prompt construction with learnable virtual type words and answer words. Then,
we synergistically optimize their representation with structured constraints.
Extensive experimental results on five datasets with standard and low-resource
settings demonstrate the effectiveness of our approach. Our code and datasets
are available in https://github.com/zjunlp/KnowPrompt for reproducibility.