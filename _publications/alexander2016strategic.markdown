---
layout: publication
title: Strategic Attentive Writer For Learning Macro-actions
authors: Alexander, Vezhnevets, Volodymyr Mnih, John Agapiou, Simon Osindero, Alex
  Graves, Oriol Vinyals, Koray Kavukcuoglu
conference: Arxiv
year: 2016
bibkey: alexander2016strategic
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.04695'}]
tags: ["Model Architecture", "Reinforcement Learning"]
short_authors: Alexander et al.
---
We present a novel deep recurrent neural network architecture that learns to
build implicit plans in an end-to-end manner by purely interacting with an
environment in reinforcement learning setting. The network builds an internal
plan, which is continuously updated upon observation of the next input from the
environment. It can also partition this internal representation into contiguous
sub- sequences by learning for how long the plan can be committed to - i.e.
followed without re-planing. Combining these properties, the proposed model,
dubbed STRategic Attentive Writer (STRAW) can learn high-level, temporally
abstracted macro- actions of varying lengths that are solely learnt from data
without any prior information. These macro-actions enable both structured
exploration and economic computation. We experimentally demonstrate that STRAW
delivers strong improvements on several ATARI games by employing temporally
extended planning strategies (e.g. Ms. Pacman and Frostbite). It is at the same
time a general algorithm that can be applied on any sequence data. To that end,
we also show that when trained on text prediction task, STRAW naturally
predicts frequent n-grams (instead of macro-actions), demonstrating the
generality of the approach.