---
layout: publication
title: A Co-interactive Transformer For Joint Slot Filling And Intent Detection
authors: Libo Qin, Tailu Liu, Wanxiang Che, Bingbing Kang, Sendong Zhao, Ting Liu
conference: ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2021
bibkey: qin2020co
citations: 123
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.03880'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Qin et al.
---
Intent detection and slot filling are two main tasks for building a spoken
language understanding (SLU) system. The two tasks are closely related and the
information of one task can be utilized in the other task. Previous studies
either model the two tasks separately or only consider the single information
flow from intent to slot. None of the prior approaches model the bidirectional
connection between the two tasks simultaneously. In this paper, we propose a
Co-Interactive Transformer to consider the cross-impact between the two tasks.
Instead of adopting the self-attention mechanism in vanilla Transformer, we
propose a co-interactive module to consider the cross-impact by building a
bidirectional connection between the two related tasks. In addition, the
proposed co-interactive module can be stacked to incrementally enhance each
other with mutual features. The experimental results on two public datasets
(SNIPS and ATIS) show that our model achieves the state-of-the-art performance
with considerable improvements (+3.4% and +0.9% on overall acc). Extensive
experiments empirically verify that our model successfully captures the mutual
interaction knowledge.