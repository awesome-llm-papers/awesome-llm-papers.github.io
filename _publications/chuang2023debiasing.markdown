---
layout: publication
title: Debiasing Vision-language Models Via Biased Prompts
authors: Ching-yao Chuang, Varun Jampani, Yuanzhen Li, Antonio Torralba, Stefanie
  Jegelka
conference: Arxiv
year: 2023
citations: 20
bibkey: chuang2023debiasing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.00070'}]
tags: [Ethics and Bias, Training Techniques, Reinforcement Learning, Applications,
  Prompting, Multimodal Models]
---
Machine learning models have been shown to inherit biases from their training
datasets. This can be particularly problematic for vision-language foundation
models trained on uncurated datasets scraped from the internet. The biases can
be amplified and propagated to downstream applications like zero-shot
classifiers and text-to-image generative models. In this study, we propose a
general approach for debiasing vision-language foundation models by projecting
out biased directions in the text embedding. In particular, we show that
debiasing only the text embedding with a calibrated projection matrix suffices
to yield robust classifiers and fair generative models. The proposed
closed-form solution enables easy integration into large-scale pipelines, and
empirical results demonstrate that our approach effectively reduces social bias
and spurious correlation in both discriminative and generative vision-language
models without the need for additional data or training.