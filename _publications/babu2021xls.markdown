---
layout: publication
title: 'XLS-R: Self-supervised Cross-lingual Speech Representation Learning At Scale'
authors: Arun Babu, Changhan Wang, Andros Tjandra, Kushal Lakhotia, Qiantong Xu, Naman
  Goyal, Kritika Singh, Patrick von Platen, Yatharth Saraf, Juan Pino, Alexei Baevski,
  Alexis Conneau, Michael Auli
conference: Interspeech 2022
year: 2022
bibkey: babu2021xls
citations: 291
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.09296'}]
tags: ["Datasets", "INTERSPEECH", "Training Techniques"]
short_authors: Babu et al.
---
This paper presents XLS-R, a large-scale model for cross-lingual speech
representation learning based on wav2vec 2.0. We train models with up to 2B
parameters on nearly half a million hours of publicly available speech audio in
128 languages, an order of magnitude more public data than the largest known
prior work. Our evaluation covers a wide range of tasks, domains, data regimes
and languages, both high and low-resource. On the CoVoST-2 speech translation
benchmark, we improve the previous state of the art by an average of 7.4 BLEU
over 21 translation directions into English. For speech recognition, XLS-R
improves over the best known prior work on BABEL, MLS, CommonVoice as well as
VoxPopuli, lowering error rates by 14-34% relative on average. XLS-R also sets
a new state of the art on VoxLingua107 language identification. Moreover, we
show that with sufficient model size, cross-lingual pretraining can outperform
English-only pretraining when translating English speech into other languages,
a setting which favors monolingual pretraining. We hope XLS-R can help to
improve speech processing tasks for many more languages of the world.