---
layout: publication
title: 'The Optimal BERT Surgeon: Scalable And Accurate Second-order Pruning For Large
  Language Models'
authors: Eldar Kurtic et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
citations: 28
bibkey: kurtic2022optimal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.07259'}, {name: Code,
    url: 'https://github.com/neuralmagic/sparseml/tree/main/research/optimal_BERT_surgeon_oBERT'}]
tags: [Has Code, Model Architecture, Distillation, Transformer, Pruning, Fine-Tuning,
  Applications, Quantization, Pre-Training, BERT, Efficiency and Optimization, Training
    Techniques, Evaluation]
---
Transformer-based language models have become a key building block for
natural language processing. While these models are extremely accurate, they
can be too large and computationally intensive to run on standard deployments.
A variety of compression methods, including distillation, quantization,
structured and unstructured pruning are known to decrease model size and
increase inference speed, with low accuracy loss. In this context, this paper's
contributions are two-fold. We perform an in-depth study of the
accuracy-compression trade-off for unstructured weight pruning of BERT models.
We introduce Optimal BERT Surgeon (oBERT), an efficient and accurate weight
pruning method based on approximate second-order information, which we show to
yield state-of-the-art results in both stages of language tasks: pre-training
and fine-tuning. Specifically, oBERT extends existing work on unstructured
second-order pruning by allowing for pruning blocks of weights, and by being
applicable at the BERT scale. Second, we investigate the impact of this pruning
method when compounding compression approaches to obtain highly compressed but
accurate models for deployment on edge devices. These models significantly push
boundaries of the current state-of-the-art sparse BERT models with respect to
all metrics: model size, inference speed and task accuracy. For example,
relative to the dense BERT-base, we obtain 10x model size compression (in MB)
with < 1% accuracy drop, 10x CPU-inference speedup with < 2% accuracy drop, and
29x CPU-inference speedup with < 7.5% accuracy drop. Our code, fully integrated
with Transformers and SparseML, is available at
https://github.com/neuralmagic/sparseml/tree/main/research/optimal_BERT_surgeon_oBERT.