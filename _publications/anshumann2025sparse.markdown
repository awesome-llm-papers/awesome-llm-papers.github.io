---
layout: publication
title: 'Sparse Logit Sampling: Accelerating Knowledge Distillation In Llms'
authors: Anshumann et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: anshumann2025sparse
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.16870'}]
tags: [Training Techniques, Distillation, CVPR, Ethics And Bias, Efficiency And Optimization]
---
Knowledge distillation can be a cost-effective technique to distill knowledge
in Large Language Models, if the teacher output logits can be pre-computed and
cached. However, successfully applying this to pre-training remains largely
unexplored. In this work, we prove that naive approaches for sparse knowledge
distillation such as caching Top-K probabilities, while intuitive, provide
biased estimates of teacher probability distribution to the student, resulting
in suboptimal performance and calibration. We propose an
importance-sampling-based method `Random Sampling Knowledge Distillation',
which provides unbiased estimates, preserves the gradient in expectation, and
requires storing significantly sparser logits. Our method enables faster
training of student models with marginal overhead (<10%) compared to
cross-entropy based training, while maintaining competitive performance
compared to full distillation, across a range of model sizes from 300M to 3B.