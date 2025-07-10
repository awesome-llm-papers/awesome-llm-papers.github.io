---
layout: publication
title: Exploring Length Generalization In Large Language Models
authors: Cem Anil et al.
conference: Arxiv
year: 2022
citations: 35
bibkey: anil2022exploring
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.04901'}]
tags: [Model Architecture, Transformer, Reinforcement Learning, In-Context Learning,
  Prompting]
---
The ability to extrapolate from short problem instances to longer ones is an
important form of out-of-distribution generalization in reasoning tasks, and is
crucial when learning from datasets where longer problem instances are rare.
These include theorem proving, solving quantitative mathematics problems, and
reading/summarizing novels. In this paper, we run careful empirical studies
exploring the length generalization capabilities of transformer-based language
models. We first establish that naively finetuning transformers on length
generalization tasks shows significant generalization deficiencies independent
of model scale. We then show that combining pretrained large language models'
in-context learning abilities with scratchpad prompting (asking the model to
output solution steps before producing an answer) results in a dramatic
improvement in length generalization. We run careful failure analyses on each
of the learning modalities and identify common sources of mistakes that
highlight opportunities in equipping language models with the ability to
generalize to longer problems.