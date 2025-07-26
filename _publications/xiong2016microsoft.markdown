---
layout: publication
title: The Microsoft 2016 Conversational Speech Recognition System
authors: W. Xiong, J. Droppo, X. Huang, F. Seide, M. Seltzer, A. Stolcke, D. Yu, G.
  Zweig
conference: 2017 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2017
bibkey: xiong2016microsoft
citations: 313
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.03528'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Xiong et al.
---
We describe Microsoft's conversational speech recognition system, in which we
combine recent developments in neural-network-based acoustic and language
modeling to advance the state of the art on the Switchboard recognition task.
Inspired by machine learning ensemble techniques, the system uses a range of
convolutional and recurrent neural networks. I-vector modeling and lattice-free
MMI training provide significant gains for all acoustic model architectures.
Language model rescoring with multiple forward and backward running RNNLMs, and
word posterior-based system combination provide a 20% boost. The best single
system uses a ResNet architecture acoustic model with RNNLM rescoring, and
achieves a word error rate of 6.9% on the NIST 2000 Switchboard task. The
combined system has an error rate of 6.2%, representing an improvement over
previously reported results on this benchmark task.