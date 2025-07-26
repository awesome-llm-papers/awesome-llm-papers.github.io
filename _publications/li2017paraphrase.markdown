---
layout: publication
title: Paraphrase Generation With Deep Reinforcement Learning
authors: Zichao Li, Xin Jiang, Lifeng Shang, Hang Li
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: li2017paraphrase
citations: 204
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.00279'}]
tags: ["EMNLP", "Reinforcement Learning"]
short_authors: Li et al.
---
Automatic generation of paraphrases from a given sentence is an important yet
challenging task in natural language processing (NLP), and plays a key role in
a number of applications such as question answering, search, and dialogue. In
this paper, we present a deep reinforcement learning approach to paraphrase
generation. Specifically, we propose a new framework for the task, which
consists of a \textit\{generator\} and an \textit\{evaluator\}, both of which are
learned from data. The generator, built as a sequence-to-sequence learning
model, can produce paraphrases given a sentence. The evaluator, constructed as
a deep matching model, can judge whether two sentences are paraphrases of each
other. The generator is first trained by deep learning and then further
fine-tuned by reinforcement learning in which the reward is given by the
evaluator. For the learning of the evaluator, we propose two methods based on
supervised learning and inverse reinforcement learning respectively, depending
on the type of available training data. Empirical study shows that the learned
evaluator can guide the generator to produce more accurate paraphrases.
Experimental results demonstrate the proposed models (the generators)
outperform the state-of-the-art methods in paraphrase generation in both
automatic evaluation and human evaluation.