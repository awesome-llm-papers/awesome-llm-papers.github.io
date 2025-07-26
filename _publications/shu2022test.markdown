---
layout: publication
title: Test-time Prompt Tuning For Zero-shot Generalization In Vision-language Models
authors: Manli Shu, Weili Nie, De-an Huang, Zhiding Yu, Tom Goldstein, Anima Anandkumar,
  Chaowei Xiao
conference: Arxiv
year: 2022
bibkey: shu2022test
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.07511'}]
tags: ["Prompting", "Training Techniques"]
short_authors: Shu et al.
---
Pre-trained vision-language models (e.g., CLIP) have shown promising
zero-shot generalization in many downstream tasks with properly designed text
prompts. Instead of relying on hand-engineered prompts, recent works learn
prompts using the training data from downstream tasks. While effective,
training on domain-specific data reduces a model's generalization capability to
unseen new domains. In this work, we propose test-time prompt tuning (TPT), a
method that can learn adaptive prompts on the fly with a single test sample.
For image classification, TPT optimizes the prompt by minimizing the entropy
with confidence selection so that the model has consistent predictions across
different augmented views of each test sample. In evaluating generalization to
natural distribution shifts, TPT improves the zero-shot top-1 accuracy of CLIP
by 3.6% on average, surpassing previous prompt tuning approaches that require
additional task-specific training data. In evaluating cross-dataset
generalization with unseen categories, TPT performs on par with the
state-of-the-art approaches that use additional training data. Project page:
https://azshue.github.io/TPT.