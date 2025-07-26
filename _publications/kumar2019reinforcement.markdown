---
layout: publication
title: Reinforcement Learning Based Curriculum Optimization For Neural Machine Translation
authors: Gaurav Kumar, George Foster, Colin Cherry, Maxim Krikun
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: kumar2019reinforcement
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.00041'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Kumar et al.
---
We consider the problem of making efficient use of heterogeneous training
data in neural machine translation (NMT). Specifically, given a training
dataset with a sentence-level feature such as noise, we seek an optimal
curriculum, or order for presenting examples to the system during training. Our
curriculum framework allows examples to appear an arbitrary number of times,
and thus generalizes data weighting, filtering, and fine-tuning schemes. Rather
than relying on prior knowledge to design a curriculum, we use reinforcement
learning to learn one automatically, jointly with the NMT system, in the course
of a single training run. We show that this approach can beat uniform and
filtering baselines on Paracrawl and WMT English-to-French datasets by up to
+3.4 BLEU, and match the performance of a hand-designed, state-of-the-art
curriculum.