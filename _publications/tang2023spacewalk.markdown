---
layout: publication
title: 'Spacewalk-18: A Benchmark For Multimodal And Long-form Procedural Video Understanding
  In Novel Domains'
authors: Tang et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: tang2023spacewalk
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.18773'}]
tags: [Training Techniques, Agentic, CVPR, Evaluation, Fine Tuning, Multimodal Models,
  Datasets]
---
Learning from (procedural) videos has increasingly served as a pathway for
embodied agents to acquire skills from human demonstrations. To do this, video
understanding models must be able to obtain structured understandings, such as
the temporal segmentation of a demonstration into sequences of actions and
skills, and to generalize the understandings to novel environments, tasks, and
problem domains. In pursuit of this goal, we introduce Spacewalk-18, a
benchmark containing two tasks: (1) step recognition and (2) video question
answering, over a dataset of temporally segmented and labeled tasks in
International Space Station spacewalk recordings. In tandem, the two tasks
quantify a model's ability to: (1) generalize to novel domains; (2) utilize
long temporal context and multimodal (e.g. visual and speech) information. Our
extensive experimental analysis highlights the challenges of Spacewalk-18, but
also suggests best practices for domain generalization and long-form
understanding. Notably, we discover a promising adaptation via summarization
technique that leads to significant performance improvement without model
fine-tuning. The Spacewalk-18 benchmark is released at
https://brown-palm.github.io/Spacewalk-18/.