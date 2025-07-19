---
layout: publication
title: 'Pykaldi2: Yet Another Speech Toolkit Based On Kaldi And Pytorch'
authors: Lu et al.
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: lu2019pykaldi2
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.05955'}]
tags: [Training Techniques, Evaluation, ICASSP, Reinforcement Learning, Applications,
  Security, Datasets]
---
We introduce PyKaldi2 speech recognition toolkit implemented based on Kaldi
and PyTorch. While similar toolkits are available built on top of the two, a
key feature of PyKaldi2 is sequence training with criteria such as MMI, sMBR
and MPE. In particular, we implemented the sequence training module with
on-the-fly lattice generation during model training in order to simplify the
training pipeline. To address the challenging acoustic environments in real
applications, PyKaldi2 also supports on-the-fly noise and reverberation
simulation to improve the model robustness. With this feature, it is possible
to backpropogate the gradients from the sequence-level loss to the front-end
feature extraction module, which, hopefully, can foster more research in the
direction of joint front-end and backend learning. We performed benchmark
experiments on Librispeech, and show that PyKaldi2 can achieve reasonable
recognition accuracy. The toolkit is released under the MIT license.