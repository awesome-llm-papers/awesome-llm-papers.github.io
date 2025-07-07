---
layout: publication
title: Multi-modal Open-domain Dialogue
authors: Kurt Shuster, Eric Michael Smith, Da Ju, Jason Weston
conference: Arxiv
year: 2020
citations: 15
bibkey: shuster2020multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.01082'}]
tags: [Training Techniques, Merging, Pre-Training, Fine-Tuning, Reinforcement Learning,
  Responsible AI, Agentic]
---
Recent work in open-domain conversational agents has demonstrated that
significant improvements in model engagingness and humanness metrics can be
achieved via massive scaling in both pre-training data and model size
(Adiwardana et al., 2020; Roller et al., 2020). However, if we want to build
agents with human-like abilities, we must expand beyond handling just text. A
particularly important topic is the ability to see images and communicate about
what is perceived. With the goal of engaging humans in multi-modal dialogue, we
investigate combining components from state-of-the-art open-domain dialogue
agents with those from state-of-the-art vision models. We study incorporating
different image fusion schemes and domain-adaptive pre-training and fine-tuning
strategies, and show that our best resulting model outperforms strong existing
models in multi-modal dialogue while simultaneously performing as well as its
predecessor (text-only) BlenderBot (Roller et al., 2020) in text-based
conversation. We additionally investigate and incorporate safety components in
our final model, and show that such efforts do not diminish model performance
with respect to engagingness metrics.