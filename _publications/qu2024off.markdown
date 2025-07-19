---
layout: publication
title: Off-the-shelf Chatgpt Is A Good Few-shot Human Motion Predictor
authors: Qu et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: qu2024off
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.15267'}]
tags: [Training Techniques, Attention Mechanism, GPT, Tools, In Context Learning,
  Model Architecture, Few Shot]
---
To facilitate the application of motion prediction in practice, recently, the
few-shot motion prediction task has attracted increasing research attention.
Yet, in existing few-shot motion prediction works, a specific model that is
dedicatedly trained over human motions is generally required. In this work,
rather than tackling this task through training a specific human motion
prediction model, we instead propose a novel FMP-OC framework. In FMP-OC, in a
totally training-free manner, we enable Few-shot Motion Prediction, which is a
non-language task, to be performed directly via utilizing the Off-the-shelf
language model ChatGPT. Specifically, to lead ChatGPT as a language model to
become an accurate motion predictor, in FMP-OC, we first introduce several
novel designs to facilitate extracting implicit knowledge from ChatGPT.
Moreover, we also incorporate our framework with a motion-in-context learning
mechanism. Extensive experiments demonstrate the efficacy of our proposed
framework.