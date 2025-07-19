---
layout: publication
title: 'Vinoground: Scrutinizing Lmms Over Dense Temporal Reasoning With Short Videos'
authors: Zhang Jianrui, Cai Mu, Lee Yong Jae
conference: Lecture Notes in Computer Science
year: 2024
bibkey: zhang2024vinoground
citations: 561
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.02763'}]
tags: [Attention Mechanism, GPT, Evaluation, Model Architecture, Multimodal Models,
  Datasets]
---
There has been growing sentiment recently that modern large multimodal models
(LMMs) have addressed most of the key challenges related to short video
comprehension. As a result, both academia and industry are gradually shifting
their attention towards the more complex challenges posed by understanding
long-form videos. However, is this really the case? Our studies indicate that
LMMs still lack many fundamental reasoning capabilities even when dealing with
short videos. We introduce Vinoground, a temporal counterfactual LMM evaluation
benchmark encompassing 1000 short and natural video-caption pairs. We
demonstrate that existing LMMs severely struggle to distinguish temporal
differences between different actions and object transformations. For example,
the best model GPT-4o only obtains ~50% on our text and video scores, showing a
large gap compared to the human baseline of ~90%. All open-source multimodal
models and CLIP-based models perform much worse, producing mostly random chance
performance. Through this work, we shed light onto the fact that temporal
reasoning in short videos is a problem yet to be fully solved. The dataset and
evaluation code are available at https://vinoground.github.io.