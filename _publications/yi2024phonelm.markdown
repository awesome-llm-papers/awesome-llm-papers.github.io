---
layout: publication
title: Phonelm:an Efficient And Capable Small Language Model Family Through Principled
  Pre-training
authors: Yi et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: yi2024phonelm
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.05046'}]
tags: [Ethics And Bias, Model Architecture, Training Techniques, Efficiency And Optimization,
  ACL, Datasets]
---
The interest in developing small language models (SLM) for on-device
deployment is fast growing. However, the existing SLM design hardly considers
the device hardware characteristics. Instead, this work presents a simple yet
effective principle for SLM design: architecture searching for (near-)optimal
runtime efficiency before pre-training. Guided by this principle, we develop
PhoneLM SLM family (currently with 0.5B and 1.5B versions), that acheive the
state-of-the-art capability-efficiency tradeoff among those with similar
parameter size. We fully open-source the code, weights, and training datasets
of PhoneLM for reproducibility and transparency, including both base and
instructed versions. We also release a finetuned version of PhoneLM capable of
accurate Android Intent invocation, and an end-to-end Android demo. All
materials are available at https://github.com/UbiquitousLearning/PhoneLM.