---
layout: publication
title: 'Skipflow: Incorporating Neural Coherence Features For End-to-end Automatic
  Text Scoring'
authors: Yi Tay, Minh C. Phan, Luu Anh Tuan, Siu Cheung Hui
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: tay2017skipflow
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.04981'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Tay et al.
---
Deep learning has demonstrated tremendous potential for Automatic Text
Scoring (ATS) tasks. In this paper, we describe a new neural architecture that
enhances vanilla neural network models with auxiliary neural coherence
features. Our new method proposes a new \textsc\{SkipFlow\} mechanism that models
relationships between snapshots of the hidden representations of a long
short-term memory (LSTM) network as it reads. Subsequently, the semantic
relationships between multiple snapshots are used as auxiliary features for
prediction. This has two main benefits. Firstly, essays are typically long
sequences and therefore the memorization capability of the LSTM network may be
insufficient. Implicit access to multiple snapshots can alleviate this problem
by acting as a protection against vanishing gradients. The parameters of the
\textsc\{SkipFlow\} mechanism also acts as an auxiliary memory. Secondly,
modeling relationships between multiple positions allows our model to learn
features that represent and approximate textual coherence. In our model, we
call this \textit\{neural coherence\} features. Overall, we present a unified
deep learning architecture that generates neural coherence features as it reads
in an end-to-end fashion. Our approach demonstrates state-of-the-art
performance on the benchmark ASAP dataset, outperforming not only feature
engineering baselines but also other deep learning models.