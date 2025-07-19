---
layout: publication
title: 'Espresso: A Fast End-to-end Neural Speech Recognition Toolkit'
authors: Wang et al.
conference: 2019 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2019
bibkey: wang2019espresso
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.08723'}]
tags: [Training Techniques, Tools, ASRU, Reinforcement Learning, Large Scale Training,
  Merging]
---
We present Espresso, an open-source, modular, extensible end-to-end neural
automatic speech recognition (ASR) toolkit based on the deep learning library
PyTorch and the popular neural machine translation toolkit fairseq. Espresso
supports distributed training across GPUs and computing nodes, and features
various decoding approaches commonly employed in ASR, including look-ahead
word-based language model fusion, for which a fast, parallelized decoder is
implemented. Espresso achieves state-of-the-art ASR performance on the WSJ,
LibriSpeech, and Switchboard data sets among other end-to-end systems without
data augmentation, and is 4--11x faster for decoding than similar systems (e.g.
ESPnet).