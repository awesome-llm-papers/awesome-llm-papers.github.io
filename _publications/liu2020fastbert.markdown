---
layout: publication
title: 'Fastbert: A Self-distilling BERT With Adaptive Inference Time'
authors: Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Haotang Deng, Qi Ju
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: liu2020fastbert
citations: 237
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.02178'}]
tags: ["Efficiency", "Fine-Tuning", "Model Architecture"]
short_authors: Liu et al.
---
Pre-trained language models like BERT have proven to be highly performant.
However, they are often computationally expensive in many practical scenarios,
for such heavy models can hardly be readily implemented with limited resources.
To improve their efficiency with an assured model performance, we propose a
novel speed-tunable FastBERT with adaptive inference time. The speed at
inference can be flexibly adjusted under varying demands, while redundant
calculation of samples is avoided. Moreover, this model adopts a unique
self-distillation mechanism at fine-tuning, further enabling a greater
computational efficacy with minimal loss in performance. Our model achieves
promising results in twelve English and Chinese datasets. It is able to speed
up by a wide range from 1 to 12 times than BERT if given different speedup
thresholds to make a speed-performance tradeoff.