---
layout: publication
title: Reinforced Multi-teacher Selection For Knowledge Distillation
authors: Fei Yuan, Linjun Shou, Jian Pei, Wutao Lin, Ming Gong, Yan Fu, Daxin Jiang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: yuan2020reinforced
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.06048'}]
tags: ["AAAI", "Training Techniques"]
short_authors: Yuan et al.
---
In natural language processing (NLP) tasks, slow inference speed and huge
footprints in GPU usage remain the bottleneck of applying pre-trained deep
models in production. As a popular method for model compression, knowledge
distillation transfers knowledge from one or multiple large (teacher) models to
a small (student) model. When multiple teacher models are available in
distillation, the state-of-the-art methods assign a fixed weight to a teacher
model in the whole distillation. Furthermore, most of the existing methods
allocate an equal weight to every teacher model. In this paper, we observe
that, due to the complexity of training examples and the differences in student
model capability, learning differentially from teacher models can lead to
better performance of student models distilled. We systematically develop a
reinforced method to dynamically assign weights to teacher models for different
training instances and optimize the performance of student model. Our extensive
experimental results on several NLP tasks clearly verify the feasibility and
effectiveness of our approach.