---
layout: publication
title: Neural Speech Synthesis With Transformer Network
authors: Naihan Li, Shujie Liu, Yanqing Liu, Sheng Zhao, Ming Liu, Ming Zhou
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: li2018neural
citations: 632
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.08895'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Li et al.
---
Although end-to-end neural text-to-speech (TTS) methods (such as Tacotron2)
are proposed and achieve state-of-the-art performance, they still suffer from
two problems: 1) low efficiency during training and inference; 2) hard to model
long dependency using current recurrent neural networks (RNNs). Inspired by the
success of Transformer network in neural machine translation (NMT), in this
paper, we introduce and adapt the multi-head attention mechanism to replace the
RNN structures and also the original attention mechanism in Tacotron2. With the
help of multi-head self-attention, the hidden states in the encoder and decoder
are constructed in parallel, which improves the training efficiency. Meanwhile,
any two inputs at different times are connected directly by self-attention
mechanism, which solves the long range dependency problem effectively. Using
phoneme sequences as input, our Transformer TTS network generates mel
spectrograms, followed by a WaveNet vocoder to output the final audio results.
Experiments are conducted to test the efficiency and performance of our new
network. For the efficiency, our Transformer TTS network can speed up the
training about 4.25 times faster compared with Tacotron2. For the performance,
rigorous human tests show that our proposed model achieves state-of-the-art
performance (outperforms Tacotron2 with a gap of 0.048) and is very close to
human quality (4.39 vs 4.44 in MOS).