---
layout: publication
title: Contrastive Attention Mechanism For Abstractive Sentence Summarization
authors: Duan et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: duan2019contrastive
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.13114'}]
tags: [RAG, EMNLP, Attention Mechanism, Tools, Evaluation, Transformer, Model Architecture,
  Reinforcement Learning, Datasets]
---
We propose a contrastive attention mechanism to extend the
sequence-to-sequence framework for abstractive sentence summarization task,
which aims to generate a brief summary of a given source sentence. The proposed
contrastive attention mechanism accommodates two categories of attention: one
is the conventional attention that attends to relevant parts of the source
sentence, the other is the opponent attention that attends to irrelevant or
less relevant parts of the source sentence. Both attentions are trained in an
opposite way so that the contribution from the conventional attention is
encouraged and the contribution from the opponent attention is discouraged
through a novel softmax and softmin functionality. Experiments on benchmark
datasets show that, the proposed contrastive attention mechanism is more
focused on the relevant parts for the summary than the conventional attention
mechanism, and greatly advances the state-of-the-art performance on the
abstractive sentence summarization task. We release the code at
https://github.com/travel-go/Abstractive-Text-Summarization