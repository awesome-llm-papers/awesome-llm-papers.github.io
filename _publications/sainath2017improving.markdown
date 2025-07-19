---
layout: publication
title: Improving The Performance Of Online Neural Transducer Models
authors: Sainath et al.
conference: 2018 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2017
bibkey: sainath2017improving
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.01807'}]
tags: [ICASSP, Model Architecture, Applications, Attention Mechanism]
---
Having a sequence-to-sequence model which can operate in an online fashion is
important for streaming applications such as Voice Search. Neural transducer is
a streaming sequence-to-sequence model, but has shown a significant degradation
in performance compared to non-streaming models such as Listen, Attend and
Spell (LAS). In this paper, we present various improvements to NT.
Specifically, we look at increasing the window over which NT computes
attention, mainly by looking backwards in time so the model still remains
online. In addition, we explore initializing a NT model from a LAS-trained
model so that it is guided with a better alignment. Finally, we explore
including stronger language models such as using wordpiece models, and applying
an external LM during the beam search. On a Voice Search task, we find with
these improvements we can get NT to match the performance of LAS.