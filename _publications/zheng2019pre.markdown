---
layout: publication
title: A Pre-training Based Personalized Dialogue Generation Model With Persona-sparse
  Data
authors: Yinhe Zheng, Rongsheng Zhang, Xiaoxi Mao, Minlie Huang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
citations: 55
bibkey: zheng2019pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.04700'}]
tags: [Model Architecture, Attention Mechanism, Pre-Training, Training Techniques,
  Evaluation]
---
Endowing dialogue systems with personas is essential to deliver more
human-like conversations. However, this problem is still far from well explored
due to the difficulties of both embodying personalities in natural languages
and the persona sparsity issue observed in most dialogue corpora. This paper
proposes a pre-training based personalized dialogue model that can generate
coherent responses using persona-sparse dialogue data. In this method, a
pre-trained language model is used to initialize an encoder and decoder, and
personal attribute embeddings are devised to model richer dialogue contexts by
encoding speakers' personas together with dialogue histories. Further, to
incorporate the target persona in the decoding process and to balance its
contribution, an attention routing structure is devised in the decoder to merge
features extracted from the target persona and dialogue contexts using
dynamically predicted weights. Our model can utilize persona-sparse dialogues
in a unified manner during the training process, and can also control the
amount of persona-related features to exhibit during the inference process.
Both automatic and manual evaluation demonstrates that the proposed model
outperforms state-of-the-art methods for generating more coherent and persona
consistent responses with persona-sparse data.