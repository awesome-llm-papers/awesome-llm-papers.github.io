---
layout: publication
title: 'Otter: A Multi-modal Model With In-context Instruction Tuning'
authors: Bo Li, Yuanhan Zhang, Liangyu Chen, Jinghao Wang, Jingkang Yang, Ziwei Liu
conference: Arxiv
year: 2023
bibkey: li2023otter
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.03726'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Li et al.
---
Large language models (LLMs) have demonstrated significant universal
capabilities as few/zero-shot learners in various tasks due to their
pre-training on vast amounts of text data, as exemplified by GPT-3, which
boosted to InstrctGPT and ChatGPT, effectively following natural language
instructions to accomplish real-world tasks. In this paper, we propose to
introduce instruction tuning into multi-modal models, motivated by the Flamingo
model's upstream interleaved format pretraining dataset. We adopt a similar
approach to construct our MultI-Modal In-Context Instruction Tuning (MIMIC-IT)
dataset. We then introduce Otter, a multi-modal model based on OpenFlamingo
(open-sourced version of DeepMind's Flamingo), trained on MIMIC-IT and
showcasing improved instruction-following ability and in-context learning. We
also optimize OpenFlamingo's implementation for researchers, democratizing the
required training resources from 1\\(\times\\) A100 GPU to 4\\(\times\\) RTX-3090 GPUs,
and integrate both OpenFlamingo and Otter into Huggingface Transformers for
more researchers to incorporate the models into their customized training and
inference pipelines.