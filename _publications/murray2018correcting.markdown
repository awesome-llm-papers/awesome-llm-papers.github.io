---
layout: publication
title: Correcting Length Bias In Neural Machine Translation
authors: Kenton Murray, David Chiang
conference: 'Proceedings of the Third Conference on Machine Translation: Research
  Papers'
year: 2018
bibkey: murray2018correcting
citations: 140
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.10006'}]
tags: ["Ethics & Fairness", "Reinforcement Learning"]
short_authors: Kenton Murray, David Chiang
---
We study two problems in neural machine translation (NMT). First, in beam
search, whereas a wider beam should in principle help translation, it often
hurts NMT. Second, NMT has a tendency to produce translations that are too
short. Here, we argue that these problems are closely related and both rooted
in label bias. We show that correcting the brevity problem almost eliminates
the beam problem; we compare some commonly-used methods for doing this, finding
that a simple per-word reward works well; and we introduce a simple and quick
way to tune this reward using the perceptron algorithm.