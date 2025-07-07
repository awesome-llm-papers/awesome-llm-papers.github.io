---
layout: publication
title: 'Prune Once For All: Sparse Pre-trained Language Models'
authors: Ofir Zafrir, Ariel Larey, Guy Boudoukh, Haihao Shen, Moshe Wasserblat
conference: Arxiv
year: 2021
citations: 26
bibkey: zafrir2021prune
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.05754'}]
tags: [Distillation, Transformer, Training Techniques, Fine-Tuning, BERT, Efficiency
    and Optimization, Applications, Pruning, Model Architecture, Quantization]
---
Transformer-based language models are applied to a wide range of applications
in natural language processing. However, they are inefficient and difficult to
deploy. In recent years, many compression algorithms have been proposed to
increase the implementation efficiency of large Transformer-based models on
target hardware. In this work we present a new method for training sparse
pre-trained Transformer language models by integrating weight pruning and model
distillation. These sparse pre-trained models can be used to transfer learning
for a wide range of tasks while maintaining their sparsity pattern. We
demonstrate our method with three known architectures to create sparse
pre-trained BERT-Base, BERT-Large and DistilBERT. We show how the compressed
sparse pre-trained models we trained transfer their knowledge to five different
downstream natural language tasks with minimal accuracy loss. Moreover, we show
how to further compress the sparse models' weights to 8bit precision using
quantization-aware training. For example, with our sparse pre-trained
BERT-Large fine-tuned on SQuADv1.1 and quantized to 8bit we achieve a
compression ratio of \\(40\\)X for the encoder with less than \\(1%\\) accuracy loss.
To the best of our knowledge, our results show the best compression-to-accuracy
ratio for BERT-Base, BERT-Large, and DistilBERT.