---
layout: publication
title: 'ARBERT & MARBERT: Deep Bidirectional Transformers For Arabic'
authors: Muhammad Abdul-mageed, Abdelrahim Elmadany, El Moatez Billah Nagoudi
conference: ACL-2021 camera ready version
year: 2020
bibkey: abdulmageed2020arbert
citations: 133
additional_links: [{name: Code, url: 'https://github.com/UBC-NLP/marbert'}, {name: Paper,
    url: 'https://arxiv.org/abs/2101.01785'}]
tags: ["Model Architecture"]
short_authors: Muhammad Abdul-mageed, Abdelrahim Elmadany, El Moatez Billah Nagoudi
---
Pre-trained language models (LMs) are currently integral to many natural
language processing systems. Although multilingual LMs were also introduced to
serve many languages, these have limitations such as being costly at inference
time and the size and diversity of non-English data involved in their
pre-training. We remedy these issues for a collection of diverse Arabic
varieties by introducing two powerful deep bidirectional transformer-based
models, ARBERT and MARBERT. To evaluate our models, we also introduce ARLUE, a
new benchmark for multi-dialectal Arabic language understanding evaluation.
ARLUE is built using 42 datasets targeting six different task clusters,
allowing us to offer a series of standardized experiments under rich
conditions. When fine-tuned on ARLUE, our models collectively achieve new
state-of-the-art results across the majority of tasks (37 out of 48
classification tasks, on the 42 datasets). Our best model acquires the highest
ARLUE score (77.40) across all six task clusters, outperforming all other
models including XLM-R Large (~ 3.4 x larger size). Our models are publicly
available at https://github.com/UBC-NLP/marbert and ARLUE will be released
through the same repository.