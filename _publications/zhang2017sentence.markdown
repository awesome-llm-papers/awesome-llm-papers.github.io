---
layout: publication
title: Sentence Simplification With Deep Reinforcement Learning
authors: Xingxing Zhang, Mirella Lapata
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: zhang2017sentence
citations: 330
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.10931'}]
tags: ["EMNLP", "Reinforcement Learning"]
short_authors: Xingxing Zhang, Mirella Lapata
---
Sentence simplification aims to make sentences easier to read and understand.
Most recent approaches draw on insights from machine translation to learn
simplification rewrites from monolingual corpora of complex and simple
sentences. We address the simplification problem with an encoder-decoder model
coupled with a deep reinforcement learning framework. Our model, which we call
\{\sc Dress\} (as shorthand for \{\bf D\}eep \{\bf RE\}inforcement \{\bf S\}entence
\{\bf S\}implification), explores the space of possible simplifications while
learning to optimize a reward function that encourages outputs which are
simple, fluent, and preserve the meaning of the input. Experiments on three
datasets demonstrate that our model outperforms competitive simplification
systems.