---
layout: publication
title: 'Codebert: A Pre-trained Model For Programming And Natural Languages'
authors: Zhangyin Feng, Daya Guo, Duyu Tang, Nan Duan, Xiaocheng Feng, Ming Gong,
  Linjun Shou, Bing Qin, Ting Liu, Daxin Jiang, Ming Zhou
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: feng2020codebert
citations: 1545
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.08155'}]
tags: ["Applications", "Datasets", "EMNLP", "Fine-Tuning", "Llm For Code", "Model Architecture", "Training Techniques"]
short_authors: Feng et al.
---
We present CodeBERT, a bimodal pre-trained model for programming language
(PL) and nat-ural language (NL). CodeBERT learns general-purpose
representations that support downstream NL-PL applications such as natural
language codesearch, code documentation generation, etc. We develop CodeBERT
with Transformer-based neural architecture, and train it with a hybrid
objective function that incorporates the pre-training task of replaced token
detection, which is to detect plausible alternatives sampled from generators.
This enables us to utilize both bimodal data of NL-PL pairs and unimodal data,
where the former provides input tokens for model training while the latter
helps to learn better generators. We evaluate CodeBERT on two NL-PL
applications by fine-tuning model parameters. Results show that CodeBERT
achieves state-of-the-art performance on both natural language code search and
code documentation generation tasks. Furthermore, to investigate what type of
knowledge is learned in CodeBERT, we construct a dataset for NL-PL probing, and
evaluate in a zero-shot setting where parameters of pre-trained models are
fixed. Results show that CodeBERT performs better than previous pre-trained
models on NL-PL probing.