---
layout: publication
title: Learning Discourse-level Diversity For Neural Dialog Models Using Conditional
  Variational Autoencoders
authors: Tiancheng Zhao, Ran Zhao, Maxine Eskenazi
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: zhao2017learning
citations: 727
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.10960'}]
tags: ["Training Techniques"]
short_authors: Tiancheng Zhao, Ran Zhao, Maxine Eskenazi
---
While recent neural encoder-decoder models have shown great promise in
modeling open-domain conversations, they often generate dull and generic
responses. Unlike past work that has focused on diversifying the output of the
decoder at word-level to alleviate this problem, we present a novel framework
based on conditional variational autoencoders that captures the discourse-level
diversity in the encoder. Our model uses latent variables to learn a
distribution over potential conversational intents and generates diverse
responses using only greedy decoders. We have further developed a novel variant
that is integrated with linguistic prior knowledge for better performance.
Finally, the training procedure is improved by introducing a bag-of-word loss.
Our proposed models have been validated to generate significantly more diverse
responses than baseline approaches and exhibit competence in discourse-level
decision-making.