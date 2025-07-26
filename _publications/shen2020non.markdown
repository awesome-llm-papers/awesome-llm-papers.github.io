---
layout: publication
title: 'Non-attentive Tacotron: Robust And Controllable Neural TTS Synthesis Including
  Unsupervised Duration Modeling'
authors: Jonathan Shen, Ye Jia, Mike Chrzanowski, Yu Zhang, Isaac Elias, Heiga Zen,
  Yonghui Wu
conference: Arxiv
year: 2020
bibkey: shen2020non
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.04301'}]
tags: ["Model Architecture"]
short_authors: Shen et al.
---
This paper presents Non-Attentive Tacotron based on the Tacotron 2
text-to-speech model, replacing the attention mechanism with an explicit
duration predictor. This improves robustness significantly as measured by
unaligned duration ratio and word deletion rate, two metrics introduced in this
paper for large-scale robustness evaluation using a pre-trained speech
recognition model. With the use of Gaussian upsampling, Non-Attentive Tacotron
achieves a 5-scale mean opinion score for naturalness of 4.41, slightly
outperforming Tacotron 2. The duration predictor enables both utterance-wide
and per-phoneme control of duration at inference time. When accurate target
durations are scarce or unavailable in the training data, we propose a method
using a fine-grained variational auto-encoder to train the duration predictor
in a semi-supervised or unsupervised manner, with results almost as good as
supervised training.