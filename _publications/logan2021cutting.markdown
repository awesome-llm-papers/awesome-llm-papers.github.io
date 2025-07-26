---
layout: publication
title: 'Cutting Down On Prompts And Parameters: Simple Few-shot Learning With Language
  Models'
authors: "Robert L. Logan Iv, Ivana Bala\u017Eevi\u0107, Eric Wallace, Fabio Petroni,\
  \ Sameer Singh, Sebastian Riedel"
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2022
bibkey: logan2021cutting
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.13353'}]
tags: ["Few-Shot", "Training Techniques"]
short_authors: Iv et al.
---
Prompting language models (LMs) with training examples and task descriptions
has been seen as critical to recent successes in few-shot learning. In this
work, we show that finetuning LMs in the few-shot setting can considerably
reduce the need for prompt engineering. In fact, one can use null prompts,
prompts that contain neither task-specific templates nor training examples, and
achieve competitive accuracy to manually-tuned prompts across a wide range of
tasks. While finetuning LMs does introduce new parameters for each downstream
task, we show that this memory overhead can be substantially reduced:
finetuning only the bias terms can achieve comparable or better accuracy than
standard finetuning while only updating 0.1% of the parameters. All in all, we
recommend finetuning LMs for few-shot learning as it is more accurate, robust
to different prompts, and can be made nearly as efficient as using frozen LMs.