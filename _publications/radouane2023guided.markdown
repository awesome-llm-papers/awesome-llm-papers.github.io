---
layout: publication
title: Guided Attention For Interpretable Motion Captioning
authors: Radouane et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2023
bibkey: radouane2023guided
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.07324'}]
tags: [Interpretability And Explainability, RAG, Training Techniques, Attention Mechanism,
  Transformer, Model Architecture, Language Modeling, AAAI]
---
Diverse and extensive work has recently been conducted on text-conditioned
human motion generation. However, progress in the reverse direction, motion
captioning, has seen less comparable advancement. In this paper, we introduce a
novel architecture design that enhances text generation quality by emphasizing
interpretability through spatio-temporal and adaptive attention mechanisms. To
encourage human-like reasoning, we propose methods for guiding attention during
training, emphasizing relevant skeleton areas over time and distinguishing
motion-related words. We discuss and quantify our model's interpretability
using relevant histograms and density distributions. Furthermore, we leverage
interpretability to derive fine-grained information about human motion,
including action localization, body part identification, and the distinction of
motion-related words. Finally, we discuss the transferability of our approaches
to other tasks. Our experiments demonstrate that attention guidance leads to
interpretable captioning while enhancing performance compared to higher
parameter-count, non-interpretable state-of-the-art systems. The code is
available at: https://github.com/rd20karim/M2T-Interpretable.