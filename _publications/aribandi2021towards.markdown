---
layout: publication
title: 'Ext5: Towards Extreme Multi-task Scaling For Transfer Learning'
authors: Vamsi Aribandi et al.
conference: Arxiv
year: 2021
citations: 72
bibkey: aribandi2021towards
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.10952'}]
tags: [Efficiency and Optimization, Training Techniques, Fine-Tuning, Pre-Training]
---
Despite the recent success of multi-task learning and transfer learning for
natural language processing (NLP), few works have systematically studied the
effect of scaling up the number of tasks during pre-training. Towards this
goal, this paper introduces ExMix (Extreme Mixture): a massive collection of
107 supervised NLP tasks across diverse domains and task-families. Using ExMix,
we study the effect of multi-task pre-training at the largest scale to date,
and analyze co-training transfer amongst common families of tasks. Through this
analysis, we show that manually curating an ideal set of tasks for multi-task
pre-training is not straightforward, and that multi-task scaling can vastly
improve models on its own. Finally, we propose ExT5: a model pre-trained using
a multi-task objective of self-supervised span denoising and supervised ExMix.
Via extensive experiments, we show that ExT5 outperforms strong T5 baselines on
SuperGLUE, GEM, Rainbow, Closed-Book QA tasks, and several tasks outside of
ExMix. ExT5 also significantly improves sample efficiency while pre-training.