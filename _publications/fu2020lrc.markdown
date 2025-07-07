---
layout: publication
title: 'LRC-BERT: Latent-representation Contrastive Knowledge Distillation For Natural
  Language Understanding'
authors: Hao Fu et al.
conference: Arxiv
year: 2020
citations: 33
bibkey: fu2020lrc
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.07335'}]
tags: [Distillation, Training Techniques, Pre-Training, BERT, Efficiency and Optimization,
  Security, Model Architecture]
---
The pre-training models such as BERT have achieved great results in various
natural language processing problems. However, a large number of parameters
need significant amounts of memory and the consumption of inference time, which
makes it difficult to deploy them on edge devices. In this work, we propose a
knowledge distillation method LRC-BERT based on contrastive learning to fit the
output of the intermediate layer from the angular distance aspect, which is not
considered by the existing distillation methods. Furthermore, we introduce a
gradient perturbation-based training architecture in the training phase to
increase the robustness of LRC-BERT, which is the first attempt in knowledge
distillation. Additionally, in order to better capture the distribution
characteristics of the intermediate layer, we design a two-stage training
method for the total distillation loss. Finally, by verifying 8 datasets on the
General Language Understanding Evaluation (GLUE) benchmark, the performance of
the proposed LRC-BERT exceeds the existing state-of-the-art methods, which
proves the effectiveness of our method.