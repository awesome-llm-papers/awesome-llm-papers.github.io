---
layout: publication
title: 'Beyond Preserved Accuracy: Evaluating Loyalty And Robustness Of BERT Compression'
authors: Canwen Xu, Wangchunshu Zhou, Tao Ge, Ke Xu, Julian Mcauley, Furu Wei
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: xu2022beyond
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.03228'}]
tags: ["Efficiency", "Evaluation", "Model Architecture"]
short_authors: Xu et al.
---
Recent studies on compression of pretrained language models (e.g., BERT)
usually use preserved accuracy as the metric for evaluation. In this paper, we
propose two new metrics, label loyalty and probability loyalty that measure how
closely a compressed model (i.e., student) mimics the original model (i.e.,
teacher). We also explore the effect of compression with regard to robustness
under adversarial attacks. We benchmark quantization, pruning, knowledge
distillation and progressive module replacing with loyalty and robustness. By
combining multiple compression techniques, we provide a practical strategy to
achieve better accuracy, loyalty and robustness.