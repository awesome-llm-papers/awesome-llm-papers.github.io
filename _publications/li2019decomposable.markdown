---
layout: publication
title: Decomposable Neural Paraphrase Generation
authors: Zichao Li, Xin Jiang, Lifeng Shang, Qun Liu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: li2019decomposable
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.09741'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Li et al.
---
Paraphrasing exists at different granularity levels, such as lexical level,
phrasal level and sentential level. This paper presents Decomposable Neural
Paraphrase Generator (DNPG), a Transformer-based model that can learn and
generate paraphrases of a sentence at different levels of granularity in a
disentangled way. Specifically, the model is composed of multiple encoders and
decoders with different structures, each of which corresponds to a specific
granularity. The empirical study shows that the decomposition mechanism of DNPG
makes paraphrase generation more interpretable and controllable. Based on DNPG,
we further develop an unsupervised domain adaptation method for paraphrase
generation. Experimental results show that the proposed model achieves
competitive in-domain performance compared to the state-of-the-art neural
models, and significantly better performance when adapting to a new domain.