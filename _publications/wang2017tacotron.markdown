---
layout: publication
title: 'Tacotron: Towards End-to-end Speech Synthesis'
authors: Yuxuan Wang, Rj Skerry-ryan, Daisy Stanton, Yonghui Wu, Ron J. Weiss, Navdeep
  Jaitly, Zongheng Yang, Ying Xiao, Zhifeng Chen, Samy Bengio, Quoc Le, Yannis Agiomyrgiannakis,
  Rob Clark, Rif A. Saurous
conference: Interspeech 2017
year: 2017
bibkey: wang2017tacotron
citations: 1519
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.10135'}]
tags: ["INTERSPEECH"]
short_authors: Wang et al.
---
A text-to-speech synthesis system typically consists of multiple stages, such
as a text analysis frontend, an acoustic model and an audio synthesis module.
Building these components often requires extensive domain expertise and may
contain brittle design choices. In this paper, we present Tacotron, an
end-to-end generative text-to-speech model that synthesizes speech directly
from characters. Given <text, audio> pairs, the model can be trained completely
from scratch with random initialization. We present several key techniques to
make the sequence-to-sequence framework perform well for this challenging task.
Tacotron achieves a 3.82 subjective 5-scale mean opinion score on US English,
outperforming a production parametric system in terms of naturalness. In
addition, since Tacotron generates speech at the frame level, it's
substantially faster than sample-level autoregressive methods.