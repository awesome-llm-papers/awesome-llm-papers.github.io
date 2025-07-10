---
layout: publication
title: Visually-prompted Language Model For Fine-grained Scene Graph Generation In
  An Open World
authors: Qifan Yu et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
citations: 15
bibkey: yu2023visually
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13233'}]
tags: [Tools, Reinforcement Learning, Multimodal Models, Prompting, Evaluation]
---
Scene Graph Generation (SGG) aims to extract <subject, predicate, object>
relationships in images for vision understanding. Although recent works have
made steady progress on SGG, they still suffer long-tail distribution issues
that tail-predicates are more costly to train and hard to distinguish due to a
small amount of annotated data compared to frequent predicates. Existing
re-balancing strategies try to handle it via prior rules but are still confined
to pre-defined conditions, which are not scalable for various models and
datasets. In this paper, we propose a Cross-modal prediCate boosting (CaCao)
framework, where a visually-prompted language model is learned to generate
diverse fine-grained predicates in a low-resource way. The proposed CaCao can
be applied in a plug-and-play fashion and automatically strengthen existing SGG
to tackle the long-tailed problem. Based on that, we further introduce a novel
Entangled cross-modal prompt approach for open-world predicate scene graph
generation (Epic), where models can generalize to unseen predicates in a
zero-shot manner. Comprehensive experiments on three benchmark datasets show
that CaCao consistently boosts the performance of multiple scene graph
generation models in a model-agnostic way. Moreover, our Epic achieves
competitive performance on open-world predicate prediction. The data and code
for this paper are publicly available.