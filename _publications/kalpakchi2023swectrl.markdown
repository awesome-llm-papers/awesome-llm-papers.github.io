---
layout: publication
title: 'Swectrl-mini: A Data-transparent Transformer-based Large Language Model For
  Controllable Text Generation In Swedish'
authors: Kalpakchi Dmytro, Boye Johan
conference: ACM Computing Surveys
year: 2023
bibkey: kalpakchi2023swectrl
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.13994'}]
tags: [Training Techniques, GPT, Prompting, Evaluation, Transformer, Model Architecture,
  Survey Paper, Language Modeling, Reinforcement Learning, Fine Tuning, Datasets]
---
We present SweCTRL-Mini, a large Swedish language model that can be used for
inference and fine-tuning on a single consumer-grade GPU. The model is based on
the CTRL architecture by Keskar, McCann, Varshney, Xiong, and Socher (2019),
which means that users of the SweCTRL-Mini model can control the genre of the
generated text by inserting special tokens in the generation prompts.
SweCTRL-Mini is trained on a subset of the Swedish part of the mC4 corpus and a
set of Swedish novels. In this article, we provide (1) a detailed account of
the utilized training data and text pre-processing steps, to the extent that it
is possible to check whether a specific phrase/source was a part of the
training data, and (2) an evaluation of the model on both discriminative tasks,
using automatic evaluation methods, and generative tasks, using human referees.
We also compare the generative capabilities of the model with those of GPT-3.
SweCTRL-Mini is fully open and available for download.