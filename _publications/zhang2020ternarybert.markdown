---
layout: publication
title: 'Ternarybert: Distillation-aware Ultra-low Bit BERT'
authors: Wei Zhang, Lu Hou, Yichun Yin, Lifeng Shang, Xiao Chen, Xin Jiang, Qun Liu
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: zhang2020ternarybert
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.12812'}]
tags: ["EMNLP", "Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Zhang et al.
---
Transformer-based pre-training models like BERT have achieved remarkable
performance in many natural language processing tasks.However, these models are
both computation and memory expensive, hindering their deployment to
resource-constrained devices. In this work, we propose TernaryBERT, which
ternarizes the weights in a fine-tuned BERT model. Specifically, we use both
approximation-based and loss-aware ternarization methods and empirically
investigate the ternarization granularity of different parts of BERT. Moreover,
to reduce the accuracy degradation caused by the lower capacity of low bits, we
leverage the knowledge distillation technique in the training process.
Experiments on the GLUE benchmark and SQuAD show that our proposed TernaryBERT
outperforms the other BERT quantization methods, and even achieves comparable
performance as the full-precision model while being 14.9x smaller.