---
layout: publication
title: Syllable-based Sequence-to-sequence Speech Recognition With The Transformer
  In Mandarin Chinese
authors: Shiyu Zhou, Linhao Dong, Shuang Xu, Bo Xu
conference: Interspeech 2018
year: 2018
bibkey: zhou2018syllable
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.10752'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Zhou et al.
---
Sequence-to-sequence attention-based models have recently shown very
promising results on automatic speech recognition (ASR) tasks, which integrate
an acoustic, pronunciation and language model into a single neural network. In
these models, the Transformer, a new sequence-to-sequence attention-based model
relying entirely on self-attention without using RNNs or convolutions, achieves
a new single-model state-of-the-art BLEU on neural machine translation (NMT)
tasks. Since the outstanding performance of the Transformer, we extend it to
speech and concentrate on it as the basic architecture of sequence-to-sequence
attention-based model on Mandarin Chinese ASR tasks. Furthermore, we
investigate a comparison between syllable based model and context-independent
phoneme (CI-phoneme) based model with the Transformer in Mandarin Chinese.
Additionally, a greedy cascading decoder with the Transformer is proposed for
mapping CI-phoneme sequences and syllable sequences into word sequences.
Experiments on HKUST datasets demonstrate that syllable based model with the
Transformer performs better than CI-phoneme based counterpart, and achieves a
character error rate (CER) of *\\(28.77%\\)*, which is competitive to the
state-of-the-art CER of \\(28.0%\\) by the joint CTC-attention based
encoder-decoder network.