---
layout: publication
title: 'Voice Transformer Network: Sequence-to-sequence Voice Conversion Using Transformer
  With Text-to-speech Pretraining'
authors: Wen-chin Huang, Tomoki Hayashi, Yi-chiao Wu, Hirokazu Kameoka, Tomoki Toda
conference: Interspeech 2020
year: 2020
bibkey: huang2019voice
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.06813'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Huang et al.
---
We introduce a novel sequence-to-sequence (seq2seq) voice conversion (VC)
model based on the Transformer architecture with text-to-speech (TTS)
pretraining. Seq2seq VC models are attractive owing to their ability to convert
prosody. While seq2seq models based on recurrent neural networks (RNNs) and
convolutional neural networks (CNNs) have been successfully applied to VC, the
use of the Transformer network, which has shown promising results in various
speech processing tasks, has not yet been investigated. Nonetheless, their
data-hungry property and the mispronunciation of converted speech make seq2seq
models far from practical. To this end, we propose a simple yet effective
pretraining technique to transfer knowledge from learned TTS models, which
benefit from large-scale, easily accessible TTS corpora. VC models initialized
with such pretrained model parameters are able to generate effective hidden
representations for high-fidelity, highly intelligible converted speech.
Experimental results show that such a pretraining scheme can facilitate
data-efficient training and outperform an RNN-based seq2seq VC model in terms
of intelligibility, naturalness, and similarity.