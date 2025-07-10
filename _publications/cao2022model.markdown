---
layout: publication
title: A Model-agnostic Data Manipulation Method For Persona-based Dialogue Generation
authors: Yu Cao, Wei Bi, Meng Fang, Shuming Shi, Dacheng Tao
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
citations: 16
bibkey: cao2022model
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.09867'}]
tags: [Model Architecture, GPT, Transformer, Agentic, Training Techniques]
---
Towards building intelligent dialogue agents, there has been a growing
interest in introducing explicit personas in generation models. However, with
limited persona-based dialogue data at hand, it may be difficult to train a
dialogue generation model well. We point out that the data challenges of this
generation task lie in two aspects: first, it is expensive to scale up current
persona-based dialogue datasets; second, each data sample in this task is more
complex to learn with than conventional dialogue data. To alleviate the above
data issues, we propose a data manipulation method, which is model-agnostic to
be packed with any persona-based dialogue generation model to improve its
performance. The original training samples will first be distilled and thus
expected to be fitted more easily. Next, we show various effective ways that
can diversify such easier distilled data. A given base model will then be
trained via the constructed data curricula, i.e. first on augmented distilled
samples and then on original ones. Experiments illustrate the superiority of
our method with two strong base dialogue models (Transformer encoder-decoder
and GPT2).