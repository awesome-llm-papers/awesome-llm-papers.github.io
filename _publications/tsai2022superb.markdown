---
layout: publication
title: 'SUPERB-SG: Enhanced Speech Processing Universal Performance Benchmark For
  Semantic And Generative Capabilities'
authors: Tsai et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: tsai2022superb
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.06849'}]
tags: [Security, Fine Tuning, Training Techniques, Evaluation, ACL, RAG, Datasets]
---
Transfer learning has proven to be crucial in advancing the state of speech
and natural language processing research in recent years. In speech, a model
pre-trained by self-supervised learning transfers remarkably well on multiple
tasks. However, the lack of a consistent evaluation methodology is limiting
towards a holistic understanding of the efficacy of such models. SUPERB was a
step towards introducing a common benchmark to evaluate pre-trained models
across various speech tasks. In this paper, we introduce SUPERB-SG, a new
benchmark focused on evaluating the semantic and generative capabilities of
pre-trained models by increasing task diversity and difficulty over SUPERB. We
use a lightweight methodology to test the robustness of representations learned
by pre-trained models under shifts in data domain and quality across different
types of tasks. It entails freezing pre-trained model parameters, only using
simple task-specific trainable heads. The goal is to be inclusive of all
researchers, and encourage efficient use of computational resources. We also
show that the task diversity of SUPERB-SG coupled with limited task supervision
is an effective recipe for evaluating the generalizability of model
representation.