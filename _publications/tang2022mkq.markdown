---
layout: publication
title: 'MKQ-BERT: Quantized BERT With 4-bits Weights And Activations'
authors: Tang et al.
conference: 2019 Fifth Workshop on Energy Efficient Machine Learning and Cognitive
  Computing - NeurIPS Edition (EMC2-NIPS)
year: 2022
bibkey: tang2022mkq
citations: 183
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13483'}]
tags: [Model Architecture, Distillation, Efficiency And Optimization, NeurIPS, BERT,
  Quantization, NEURIPS, Transformer]
---
Recently, pre-trained Transformer based language models, such as BERT, have
shown great superiority over the traditional methods in many Natural Language
Processing (NLP) tasks. However, the computational cost for deploying these
models is prohibitive on resource-restricted devices. One method to alleviate
this computation overhead is to quantize the original model into fewer bits
representation, and previous work has proved that we can at most quantize both
weights and activations of BERT into 8-bits, without degrading its performance.
In this work, we propose MKQ-BERT, which further improves the compression level
and uses 4-bits for quantization. In MKQ-BERT, we propose a novel way for
computing the gradient of the quantization scale, combined with an advanced
distillation strategy. On the one hand, we prove that MKQ-BERT outperforms the
existing BERT quantization methods for achieving a higher accuracy under the
same compression level. On the other hand, we are the first work that
successfully deploys the 4-bits BERT and achieves an end-to-end speedup for
inference. Our results suggest that we could achieve 5.3x of bits reduction
without degrading the model accuracy, and the inference speed of one int4 layer
is 15x faster than a float32 layer in Transformer based model.