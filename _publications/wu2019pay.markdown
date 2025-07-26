---
layout: publication
title: Pay Less Attention With Lightweight And Dynamic Convolutions
authors: Felix Wu, Angela Fan, Alexei Baevski, Yann N. Dauphin, Michael Auli
conference: Arxiv
year: 2019
bibkey: wu2019pay
citations: 349
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.10430'}]
tags: ["Evaluation"]
short_authors: Wu et al.
---
Self-attention is a useful mechanism to build generative models for language
and images. It determines the importance of context elements by comparing each
element to the current time step. In this paper, we show that a very
lightweight convolution can perform competitively to the best reported
self-attention results. Next, we introduce dynamic convolutions which are
simpler and more efficient than self-attention. We predict separate convolution
kernels based solely on the current time-step in order to determine the
importance of context elements. The number of operations required by this
approach scales linearly in the input length, whereas self-attention is
quadratic. Experiments on large-scale machine translation, language modeling
and abstractive summarization show that dynamic convolutions improve over
strong self-attention models. On the WMT'14 English-German test set dynamic
convolutions achieve a new state of the art of 29.7 BLEU.