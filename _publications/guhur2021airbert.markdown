---
layout: publication
title: 'Airbert: In-domain Pretraining For Vision-and-language Navigation'
authors: Pierre-louis Guhur, Makarand Tapaswi, Shizhe Chen, Ivan Laptev, Cordelia
  Schmid
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: guhur2021airbert
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.09105'}]
tags: ["ICCV", "Training Techniques"]
short_authors: Guhur et al.
---
Vision-and-language navigation (VLN) aims to enable embodied agents to
navigate in realistic environments using natural language instructions. Given
the scarcity of domain-specific training data and the high diversity of image
and language inputs, the generalization of VLN agents to unseen environments
remains challenging. Recent methods explore pretraining to improve
generalization, however, the use of generic image-caption datasets or existing
small-scale VLN environments is suboptimal and results in limited improvements.
In this work, we introduce BnB, a large-scale and diverse in-domain VLN
dataset. We first collect image-caption (IC) pairs from hundreds of thousands
of listings from online rental marketplaces. Using IC pairs we next propose
automatic strategies to generate millions of VLN path-instruction (PI) pairs.
We further propose a shuffling loss that improves the learning of temporal
order inside PI pairs. We use BnB pretrain our Airbert model that can be
adapted to discriminative and generative settings and show that it outperforms
state of the art for Room-to-Room (R2R) navigation and Remote Referring
Expression (REVERIE) benchmarks. Moreover, our in-domain pretraining
significantly increases performance on a challenging few-shot VLN evaluation,
where we train the model only on VLN instructions from a few houses.