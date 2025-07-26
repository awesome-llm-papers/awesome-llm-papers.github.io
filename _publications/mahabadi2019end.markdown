---
layout: publication
title: End-to-end Bias Mitigation By Modelling Biases In Corpora
authors: Rabeeh Karimi Mahabadi, Yonatan Belinkov, James Henderson
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: mahabadi2019end
citations: 140
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06321'}]
tags: ["Datasets", "Has Code", "Training Techniques"]
short_authors: Rabeeh Karimi Mahabadi, Yonatan Belinkov, James Henderson
---
Several recent studies have shown that strong natural language understanding
(NLU) models are prone to relying on unwanted dataset biases without learning
the underlying task, resulting in models that fail to generalize to
out-of-domain datasets and are likely to perform poorly in real-world
scenarios. We propose two learning strategies to train neural models, which are
more robust to such biases and transfer better to out-of-domain datasets. The
biases are specified in terms of one or more bias-only models, which learn to
leverage the dataset biases. During training, the bias-only models' predictions
are used to adjust the loss of the base model to reduce its reliance on biases
by down-weighting the biased examples and focusing the training on the hard
examples. We experiment on large-scale natural language inference and fact
verification benchmarks, evaluating on out-of-domain datasets that are
specifically designed to assess the robustness of models against known biases
in the training data. Results show that our debiasing methods greatly improve
robustness in all settings and better transfer to other textual entailment
datasets. Our code and data are publicly available in
https://github.com/rabeehk/robust-nli.