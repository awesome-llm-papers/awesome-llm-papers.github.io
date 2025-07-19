---
layout: publication
title: 'AMTSS: An Adaptive Multi-teacher Single-student Knowledge Distillation Framework
  For Multilingual Language Inference'
authors: Chen et al.
conference: Neurocomputing
year: 2023
bibkey: chen2023amtss
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.07928'}]
tags: [Distillation, Tools, Efficiency And Optimization, Reinforcement Learning, Applications,
  Datasets]
---
Knowledge distillation is of key importance to launching multilingual
pre-trained language models for real applications. To support cost-effective
language inference in multilingual settings, we propose AMTSS, an adaptive
multi-teacher single-student distillation framework, which allows distilling
knowledge from multiple teachers to a single student. We first introduce an
adaptive learning strategy and teacher importance weight, which enables a
student to effectively learn from max-margin teachers and easily adapt to new
languages. Moreover, we present a shared student encoder with different
projection layers in support of multiple languages, which contributes to
largely reducing development and machine cost. Experimental results show that
AMTSS gains competitive results on the public XNLI dataset and the realistic
industrial dataset AliExpress (AE) in the E-commerce scenario.