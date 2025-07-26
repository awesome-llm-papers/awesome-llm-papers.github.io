---
layout: publication
title: End-to-end Adversarial Text-to-speech
authors: "Jeff Donahue, Sander Dieleman, Miko\u0142aj Bi\u0144kowski, Erich Elsen,\
  \ Karen Simonyan"
conference: Arxiv
year: 2020
bibkey: donahue2020end
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.03575'}]
tags: ["Training Techniques"]
short_authors: Donahue et al.
---
Modern text-to-speech synthesis pipelines typically involve multiple
processing stages, each of which is designed or learnt independently from the
rest. In this work, we take on the challenging task of learning to synthesise
speech from normalised text or phonemes in an end-to-end manner, resulting in
models which operate directly on character or phoneme input sequences and
produce raw speech audio outputs. Our proposed generator is feed-forward and
thus efficient for both training and inference, using a differentiable
alignment scheme based on token length prediction. It learns to produce high
fidelity audio through a combination of adversarial feedback and prediction
losses constraining the generated audio to roughly match the ground truth in
terms of its total duration and mel-spectrogram. To allow the model to capture
temporal variation in the generated audio, we employ soft dynamic time warping
in the spectrogram-based prediction loss. The resulting model achieves a mean
opinion score exceeding 4 on a 5 point scale, which is comparable to the
state-of-the-art models relying on multi-stage training and additional
supervision.