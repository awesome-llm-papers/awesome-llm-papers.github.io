---
layout: publication
title: 'Lightseq: A High Performance Inference Library For Transformers'
authors: Xiaohui Wang, Ying Xiong, Yang Wei, Mingxuan Wang, Lei Li
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies: Industry
  Papers'
year: 2020
citations: 16
bibkey: wang2020high
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.13887'}, {name: Code,
    url: 'https://github.com/bytedance/lightseq'}]
tags: [Has Code, Model Architecture, Transformer, Applications, Tools, Efficiency
    and Optimization, BERT, Evaluation]
---
Transformer, BERT and their variants have achieved great success in natural
language processing. Since Transformer models are huge in size, serving these
models is a challenge for real industrial applications. In this paper, we
propose LightSeq, a highly efficient inference library for models in the
Transformer family. LightSeq includes a series of GPU optimization techniques
to to streamline the computation of neural layers and to reduce memory
footprint. LightSeq can easily import models trained using PyTorch and
Tensorflow. Experimental results on machine translation benchmarks show that
LightSeq achieves up to 14x speedup compared with TensorFlow and 1.4x compared
with FasterTransformer, a concurrent CUDA implementation. The code is available
at https://github.com/bytedance/lightseq.