---
layout: publication
title: An Analysis Of Incorporating An External Language Model Into A Sequence-to-sequence
  Model
authors: Anjuli Kannan, Yonghui Wu, Patrick Nguyen, Tara N. Sainath, Zhifeng Chen,
  Rohit Prabhavalkar
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2018
bibkey: kannan2017analysis
citations: 254
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.01996'}]
tags: ["ICASSP", "Model Architecture"]
short_authors: Kannan et al.
---
Attention-based sequence-to-sequence models for automatic speech recognition
jointly train an acoustic model, language model, and alignment mechanism. Thus,
the language model component is only trained on transcribed audio-text pairs.
This leads to the use of shallow fusion with an external language model at
inference time. Shallow fusion refers to log-linear interpolation with a
separately trained language model at each step of the beam search. In this
work, we investigate the behavior of shallow fusion across a range of
conditions: different types of language models, different decoding units, and
different tasks. On Google Voice Search, we demonstrate that the use of shallow
fusion with a neural LM with wordpieces yields a 9.1% relative word error rate
reduction (WERR) over our competitive attention-based sequence-to-sequence
model, obviating the need for second-pass rescoring.