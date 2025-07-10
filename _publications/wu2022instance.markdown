---
layout: publication
title: 'IDPG: An Instance-dependent Prompt Generation Method'
authors: Zhuofeng Wu et al.
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
citations: 17
bibkey: wu2022instance
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.04497'}]
tags: [Training Techniques, Fine-Tuning, Prompting]
---
Prompt tuning is a new, efficient NLP transfer learning paradigm that adds a
task-specific prompt in each input instance during the model training stage. It
freezes the pre-trained language model and only optimizes a few task-specific
prompts. In this paper, we propose a conditional prompt generation method to
generate prompts for each input instance, referred to as the Instance-Dependent
Prompt Generation (IDPG). Unlike traditional prompt tuning methods that use a
fixed prompt, IDPG introduces a lightweight and trainable component to generate
prompts based on each input sentence. Extensive experiments on ten natural
language understanding (NLU) tasks show that the proposed strategy consistently
outperforms various prompt tuning baselines and is on par with other efficient
transfer learning methods such as Compacter while tuning far fewer model
parameters.