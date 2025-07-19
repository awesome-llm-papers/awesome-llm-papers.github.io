---
layout: publication
title: Streaming Automatic Speech Recognition With The Transformer Model
authors: Moritz Niko, Hori Takaaki, Roux Jonathan Le
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: moritz2020streaming
citations: 200
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.02674'}]
tags: [ICASSP, Model Architecture, Attention Mechanism, Transformer]
---
Encoder-decoder based sequence-to-sequence models have demonstrated
state-of-the-art results in end-to-end automatic speech recognition (ASR).
Recently, the transformer architecture, which uses self-attention to model
temporal context information, has been shown to achieve significantly lower
word error rates (WERs) compared to recurrent neural network (RNN) based system
architectures. Despite its success, the practical usage is limited to offline
ASR tasks, since encoder-decoder architectures typically require an entire
speech utterance as input. In this work, we propose a transformer based
end-to-end ASR system for streaming ASR, where an output must be generated
shortly after each spoken word. To achieve this, we apply time-restricted
self-attention for the encoder and triggered attention for the encoder-decoder
attention mechanism. Our proposed streaming transformer architecture achieves
2.8% and 7.2% WER for the "clean" and "other" test data of LibriSpeech, which
to our knowledge is the best published streaming end-to-end ASR result for this
task.