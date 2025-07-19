---
layout: publication
title: 'Infobert: Improving Robustness Of Language Models From An Information Theoretic
  Perspective'
authors: Wang et al.
conference: Arxiv
year: 2020
bibkey: wang2020infobert
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02329'}]
tags: [Training Techniques, Tools, BERT, Model Architecture, Security, Fine Tuning,
  Datasets]
---
Large-scale language models such as BERT have achieved state-of-the-art
performance across a wide range of NLP tasks. Recent studies, however, show
that such BERT-based models are vulnerable facing the threats of textual
adversarial attacks. We aim to address this problem from an
information-theoretic perspective, and propose InfoBERT, a novel learning
framework for robust fine-tuning of pre-trained language models. InfoBERT
contains two mutual-information-based regularizers for model training: (i) an
Information Bottleneck regularizer, which suppresses noisy mutual information
between the input and the feature representation; and (ii) a Robust Feature
regularizer, which increases the mutual information between local robust
features and global features. We provide a principled way to theoretically
analyze and improve the robustness of representation learning for language
models in both standard and adversarial training. Extensive experiments
demonstrate that InfoBERT achieves state-of-the-art robust accuracy over
several adversarial datasets on Natural Language Inference (NLI) and Question
Answering (QA) tasks. Our code is available at
https://github.com/AI-secure/InfoBERT.