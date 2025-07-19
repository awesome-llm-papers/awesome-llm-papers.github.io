---
layout: publication
title: Model State Arithmetic For Machine Unlearning
authors: Rezaei et al.
conference: 2021 IEEE Symposium on Security and Privacy (SP)
year: 2025
bibkey: rezaei2025model
citations: 338
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.20941'}]
tags: [Security, Training Techniques, Evaluation, RAG, Privacy, Datasets]
---
Large language models are trained on massive corpora of web data, which may include private data, copyrighted material, factually inaccurate data, or data that degrades model performance. Eliminating the influence of such problematic datapoints through complete retraining -- by repeatedly pretraining the model on datasets that exclude these specific instances -- is computationally prohibitive. For this reason, unlearning algorithms have emerged that aim to eliminate the influence of particular datapoints, while otherwise preserving the model -- at a low computational cost. However, precisely estimating and undoing the influence of individual datapoints has proved to be challenging. In this work, we propose a new algorithm, MSA, for estimating and undoing the influence of datapoints -- by leveraging model checkpoints i.e. artifacts capturing model states at different stages of pretraining. Our experimental results demonstrate that MSA consistently outperforms existing machine unlearning algorithms across multiple benchmarks, models, and evaluation metrics, suggesting that MSA could be an effective approach towards more flexible large language models that are capable of data erasure.