---
layout: publication
title: Do Llms Exhibit Human-like Response Biases? A Case Study In Survey Design
authors: Lindia Tjuatja, Valerie Chen, Sherry Tongshuang Wu, Ameet Talwalkar, Graham
  Neubig
conference: Transactions of the Association for Computational Linguistics
year: 2023
citations: 16
bibkey: tjuatja2023do
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.04076'}, {name: Code,
    url: 'https://github.com/lindiatjuatja/BiasMonkey'}]
tags: [Has Code, Ethics and Bias, Survey Paper, Tools, Reinforcement Learning, Prompting,
  Evaluation]
---
As large language models (LLMs) become more capable, there is growing
excitement about the possibility of using LLMs as proxies for humans in
real-world tasks where subjective labels are desired, such as in surveys and
opinion polling. One widely-cited barrier to the adoption of LLMs as proxies
for humans in subjective tasks is their sensitivity to prompt wording - but
interestingly, humans also display sensitivities to instruction changes in the
form of response biases. We investigate the extent to which LLMs reflect human
response biases, if at all. We look to survey design, where human response
biases caused by changes in the wordings of "prompts" have been extensively
explored in social psychology literature. Drawing from these works, we design a
dataset and framework to evaluate whether LLMs exhibit human-like response
biases in survey questionnaires. Our comprehensive evaluation of nine models
shows that popular open and commercial LLMs generally fail to reflect
human-like behavior, particularly in models that have undergone RLHF.
Furthermore, even if a model shows a significant change in the same direction
as humans, we find that they are sensitive to perturbations that do not elicit
significant changes in humans. These results highlight the pitfalls of using
LLMs as human proxies, and underscore the need for finer-grained
characterizations of model behavior. Our code, dataset, and collected samples
are available at https://github.com/lindiatjuatja/BiasMonkey