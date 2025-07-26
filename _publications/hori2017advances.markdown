---
layout: publication
title: Advances In Joint Ctc-attention Based End-to-end Speech Recognition With A
  Deep CNN Encoder And RNN-LM
authors: Takaaki Hori, Shinji Watanabe, Yu Zhang, William Chan
conference: Interspeech 2017
year: 2017
bibkey: hori2017advances
citations: 318
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.02737'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Hori et al.
---
We present a state-of-the-art end-to-end Automatic Speech Recognition (ASR)
model. We learn to listen and write characters with a joint Connectionist
Temporal Classification (CTC) and attention-based encoder-decoder network. The
encoder is a deep Convolutional Neural Network (CNN) based on the VGG network.
The CTC network sits on top of the encoder and is jointly trained with the
attention-based decoder. During the beam search process, we combine the CTC
predictions, the attention-based decoder predictions and a separately trained
LSTM language model. We achieve a 5-10% error reduction compared to prior
systems on spontaneous Japanese and Chinese speech, and our end-to-end model
beats out traditional hybrid ASR systems.