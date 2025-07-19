---
layout: publication
title: Explainable Outfit Recommendation With Joint Outfit Matching And Comment Generation
authors: Lin et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2018
bibkey: lin2018explainable
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.08977'}]
tags: [Interpretability And Explainability, Attention Mechanism, Tools, Transformer,
  Model Architecture, Reinforcement Learning, Multimodal Models, Datasets]
---
Most previous work on outfit recommendation focuses on designing visual
features to enhance recommendations. Existing work neglects user comments of
fashion items, which have been proved to be effective in generating
explanations along with better recommendation results. We propose a novel
neural network framework, neural outfit recommendation (NOR), that
simultaneously provides outfit recommendations and generates abstractive
comments. NOR consists of two parts: outfit matching and comment generation.
For outfit matching, we propose a convolutional neural network with a mutual
attention mechanism to extract visual features. The visual features are then
decoded into a rating score for the matching prediction. For abstractive
comment generation, we propose a gated recurrent neural network with a
cross-modality attention mechanism to transform visual features into a concise
sentence. The two parts are jointly trained based on a multi-task learning
framework in an end-to-end back-propagation paradigm. Extensive experiments
conducted on an existing dataset and a collected real-world dataset show NOR
achieves significant improvements over state-of-the-art baselines for outfit
recommendation. Meanwhile, our generated comments achieve impressive ROUGE and
BLEU scores in comparison to human-written comments. The generated comments can
be regarded as explanations for the recommendation results. We release the
dataset and code to facilitate future research.