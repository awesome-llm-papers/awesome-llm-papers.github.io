---
layout: publication
title: 'Longt5: Efficient Text-to-text Transformer For Long Sequences'
authors: Mandy Guo, Joshua Ainslie, David Uthus, Santiago Ontanon, Jianmo Ni, Yun-hsuan
  Sung, Yinfei Yang
conference: 'Findings of the Association for Computational Linguistics: NAACL 2022'
year: 2022
bibkey: guo2021longt5
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.07916'}]
tags: ["Model Architecture", "NAACL"]
short_authors: Guo et al.
---
Recent work has shown that either (1) increasing the input length or (2)
increasing model size can improve the performance of Transformer-based neural
models. In this paper, we present a new model, called LongT5, with which we
explore the effects of scaling both the input length and model size at the same
time. Specifically, we integrated attention ideas from long-input transformers
(ETC), and adopted pre-training strategies from summarization pre-training
(PEGASUS) into the scalable T5 architecture. The result is a new attention
mechanism we call \{\em Transient Global\} (TGlobal), which mimics ETC's
local/global attention mechanism, but without requiring additional side-inputs.
We are able to achieve state-of-the-art results on several summarization tasks
and outperform the original T5 models on question answering tasks.