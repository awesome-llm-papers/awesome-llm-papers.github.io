---
layout: publication
title: 'Wenet 2.0: More Productive End-to-end Speech Recognition Toolkit'
authors: Binbin Zhang, di Wu, Zhendong Peng, Xingchen Song, Zhuoyuan Yao, Hang Lv,
  Lei Xie, Chao Yang, Fuping Pan, Jianwei Niu
conference: Interspeech 2022
year: 2022
bibkey: zhang2022wenet
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.15455'}]
tags: ["INTERSPEECH", "Tools"]
short_authors: Zhang et al.
---
Recently, we made available WeNet, a production-oriented end-to-end speech
recognition toolkit, which introduces a unified two-pass (U2) framework and a
built-in runtime to address the streaming and non-streaming decoding modes in a
single model. To further improve ASR performance and facilitate various
production requirements, in this paper, we present WeNet 2.0 with four
important updates. (1) We propose U2++, a unified two-pass framework with
bidirectional attention decoders, which includes the future contextual
information by a right-to-left attention decoder to improve the representative
ability of the shared encoder and the performance during the rescoring stage.
(2) We introduce an n-gram based language model and a WFST-based decoder into
WeNet 2.0, promoting the use of rich text data in production scenarios. (3) We
design a unified contextual biasing framework, which leverages user-specific
context (e.g., contact lists) to provide rapid adaptation ability for
production and improves ASR accuracy in both with-LM and without-LM scenarios.
(4) We design a unified IO to support large-scale data for effective model
training. In summary, the brand-new WeNet 2.0 achieves up to 10% relative
recognition performance improvement over the original WeNet on various corpora
and makes available several important production-oriented features.