---
layout: publication
title: 'Ernie-vil: Knowledge Enhanced Vision-language Representations Through Scene
  Graph'
authors: Yu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: yu2020ernie
citations: 181
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.16934'}]
tags: [Training Techniques, Evaluation, Multimodal Models, AAAI, Datasets]
---
We propose a knowledge-enhanced approach, ERNIE-ViL, which incorporates
structured knowledge obtained from scene graphs to learn joint representations
of vision-language. ERNIE-ViL tries to build the detailed semantic connections
(objects, attributes of objects and relationships between objects) across
vision and language, which are essential to vision-language cross-modal tasks.
Utilizing scene graphs of visual scenes, ERNIE-ViL constructs Scene Graph
Prediction tasks, i.e., Object Prediction, Attribute Prediction and
Relationship Prediction tasks in the pre-training phase. Specifically, these
prediction tasks are implemented by predicting nodes of different types in the
scene graph parsed from the sentence. Thus, ERNIE-ViL can learn the joint
representations characterizing the alignments of the detailed semantics across
vision and language. After pre-training on large scale image-text aligned
datasets, we validate the effectiveness of ERNIE-ViL on 5 cross-modal
downstream tasks. ERNIE-ViL achieves state-of-the-art performances on all these
tasks and ranks the first place on the VCR leaderboard with an absolute
improvement of 3.7%.