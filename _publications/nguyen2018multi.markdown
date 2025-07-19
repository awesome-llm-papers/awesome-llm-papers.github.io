---
layout: publication
title: Multi-task Learning Of Hierarchical Vision-language Representation
authors: Nguyen Duy-kien, Okatani Takayuki
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2018
bibkey: nguyen2018multi
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.00500'}]
tags: [Attention Mechanism, Alt, CVPR, Model Architecture, Multimodal Models, Datasets]
---
It is still challenging to build an AI system that can perform tasks that
involve vision and language at human level. So far, researchers have singled
out individual tasks separately, for each of which they have designed networks
and trained them on its dedicated datasets. Although this approach has seen a
certain degree of success, it comes with difficulties of understanding
relations among different tasks and transferring the knowledge learned for a
task to others. We propose a multi-task learning approach that enables to learn
vision-language representation that is shared by many tasks from their diverse
datasets. The representation is hierarchical, and prediction for each task is
computed from the representation at its corresponding level of the hierarchy.
We show through experiments that our method consistently outperforms previous
single-task-learning methods on image caption retrieval, visual question
answering, and visual grounding. We also analyze the learned hierarchical
representation by visualizing attention maps generated in our network.