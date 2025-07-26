---
layout: publication
title: Neural Keyphrase Generation Via Reinforcement Learning With Adaptive Rewards
authors: Hou Pong Chan, Wang Chen, Lu Wang, Irwin King
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: chan2019neural
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.04106'}]
tags: ["Reinforcement Learning"]
short_authors: Chan et al.
---
Generating keyphrases that summarize the main points of a document is a
fundamental task in natural language processing. Although existing generative
models are capable of predicting multiple keyphrases for an input document as
well as determining the number of keyphrases to generate, they still suffer
from the problem of generating too few keyphrases. To address this problem, we
propose a reinforcement learning (RL) approach for keyphrase generation, with
an adaptive reward function that encourages a model to generate both sufficient
and accurate keyphrases. Furthermore, we introduce a new evaluation method that
incorporates name variations of the ground-truth keyphrases using the Wikipedia
knowledge base. Thus, our evaluation method can more robustly evaluate the
quality of predicted keyphrases. Extensive experiments on five real-world
datasets of different scales demonstrate that our RL approach consistently and
significantly improves the performance of the state-of-the-art generative
models with both conventional and new evaluation methods.