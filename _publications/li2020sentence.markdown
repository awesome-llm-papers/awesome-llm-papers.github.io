---
layout: publication
title: On The Sentence Embeddings From Pre-trained Language Models
authors: Li et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: li2020sentence
citations: 481
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.05864'}]
tags: [Training Techniques, EMNLP, Masked Language Model, BERT, Model Architecture,
  Reinforcement Learning, Fine Tuning]
---
Pre-trained contextual representations like BERT have achieved great success
in natural language processing. However, the sentence embeddings from the
pre-trained language models without fine-tuning have been found to poorly
capture semantic meaning of sentences. In this paper, we argue that the
semantic information in the BERT embeddings is not fully exploited. We first
reveal the theoretical connection between the masked language model
pre-training objective and the semantic similarity task theoretically, and then
analyze the BERT sentence embeddings empirically. We find that BERT always
induces a non-smooth anisotropic semantic space of sentences, which harms its
performance of semantic similarity. To address this issue, we propose to
transform the anisotropic sentence embedding distribution to a smooth and
isotropic Gaussian distribution through normalizing flows that are learned with
an unsupervised objective. Experimental results show that our proposed
BERT-flow method obtains significant performance gains over the
state-of-the-art sentence embeddings on a variety of semantic textual
similarity tasks. The code is available at
https://github.com/bohanli/BERT-flow.