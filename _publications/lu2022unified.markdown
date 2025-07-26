---
layout: publication
title: Unified BERT For Few-shot Natural Language Understanding
authors: Junyu Lu, Ping Yang, Ruyi Gan, Jing Yang, Jiaxing Zhang
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: lu2022unified
citations: 270
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.12094'}]
tags: ["Few-Shot", "Model Architecture", "Training Techniques"]
short_authors: Lu et al.
---
Even as pre-trained language models share a semantic encoder, natural
language understanding suffers from a diversity of output schemas. In this
paper, we propose UBERT, a unified bidirectional language understanding model
based on BERT framework, which can universally model the training objects of
different NLU tasks through a biaffine network. Specifically, UBERT encodes
prior knowledge from various aspects, uniformly constructing learning
representations across multiple NLU tasks, which is conducive to enhancing the
ability to capture common semantic understanding. By using the biaffine to
model scores pair of the start and end position of the original text, various
classification and extraction structures can be converted into a universal,
span-decoding approach. Experiments show that UBERT wins the first price in the
2022 AIWIN - World Artificial Intelligence Innovation Competition, Chinese
insurance few-shot multi-task track, and realizes the unification of extensive
information extraction and linguistic reasoning tasks.