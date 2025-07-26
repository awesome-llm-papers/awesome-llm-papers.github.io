---
layout: publication
title: 'Emformer: Efficient Memory Transformer Based Acoustic Model For Low Latency
  Streaming Speech Recognition'
authors: Yangyang Shi, Yongqiang Wang, Chunyang Wu, Ching-feng Yeh, Julian Chan, Frank
  Zhang, Duc Le, Mike Seltzer
conference: ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2021
bibkey: shi2020emformer
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.10759'}]
tags: ["ICASSP", "Memory & Context", "Model Architecture"]
short_authors: Shi et al.
---
This paper proposes an efficient memory transformer Emformer for low latency
streaming speech recognition. In Emformer, the long-range history context is
distilled into an augmented memory bank to reduce self-attention's computation
complexity. A cache mechanism saves the computation for the key and value in
self-attention for the left context. Emformer applies a parallelized block
processing in training to support low latency models. We carry out experiments
on benchmark LibriSpeech data. Under average latency of 960 ms, Emformer gets
WER \\(2.50%\\) on test-clean and \\(5.62%\\) on test-other. Comparing with a strong
baseline augmented memory transformer (AM-TRF), Emformer gets \\(4.6\\) folds
training speedup and \\(18%\\) relative real-time factor (RTF) reduction in
decoding with relative WER reduction \\(17%\\) on test-clean and \\(9%\\) on
test-other. For a low latency scenario with an average latency of 80 ms,
Emformer achieves WER \\(3.01%\\) on test-clean and \\(7.09%\\) on test-other.
Comparing with the LSTM baseline with the same latency and model size, Emformer
gets relative WER reduction \\(9%\\) and \\(16%\\) on test-clean and test-other,
respectively.