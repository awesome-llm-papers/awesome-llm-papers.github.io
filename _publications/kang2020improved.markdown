---
layout: publication
title: Improved Natural Language Generation Via Loss Truncation
authors: Daniel Kang, Tatsunori Hashimoto
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: kang2020improved
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14589'}]
tags: ["Training Techniques"]
short_authors: Daniel Kang, Tatsunori Hashimoto
---
Neural language models are usually trained to match the distributional
properties of a large-scale corpus by minimizing the log loss. While
straightforward to optimize, this approach forces the model to reproduce all
variations in the dataset, including noisy and invalid references (e.g.,
misannotation and hallucinated facts). Worse, the commonly used log loss is
overly sensitive to such phenomena and even a small fraction of noisy data can
degrade performance. In this work, we show that the distinguishability of the
models and reference serves as a principled and robust alternative for handling
invalid references. To optimize distinguishability, we propose loss truncation,
which adaptively removes high loss examples during training. We show this is as
easy to optimize as log loss and tightly bounds distinguishability under noise.
Empirically, we demonstrate that loss truncation outperforms existing baselines
on distinguishability on a summarization task, and show that samples generated
by the loss truncation model have factual accuracy ratings that exceed those of
baselines and match human references.