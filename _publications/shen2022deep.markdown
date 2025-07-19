---
layout: publication
title: Deep Latent-variable Models For Text Generation
authors: Shen Xiaoyu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2022
bibkey: shen2022deep
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.02055'}]
tags: [Interpretability And Explainability, Training Techniques, EMNLP, Model Architecture,
  Language Modeling, Applications]
---
Text generation aims to produce human-like natural language output for
down-stream tasks. It covers a wide range of applications like machine
translation, document summarization, dialogue generation and so on. Recently
deep neural network-based end-to-end architectures have been widely adopted.
The end-to-end approach conflates all sub-modules, which used to be designed by
complex handcrafted rules, into a holistic encode-decode architecture. Given
enough training data, it is able to achieve state-of-the-art performance yet
avoiding the need of language/domain-dependent knowledge. Nonetheless, deep
learning models are known to be extremely data-hungry, and text generated from
them usually suffer from low diversity, interpretability and controllability.
As a result, it is difficult to trust the output from them in real-life
applications. Deep latent-variable models, by specifying the probabilistic
distribution over an intermediate latent process, provide a potential way of
addressing these problems while maintaining the expressive power of deep neural
networks. This dissertation presents how deep latent-variable models can
improve over the standard encoder-decoder model for text generation.