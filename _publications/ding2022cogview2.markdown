---
layout: publication
title: 'Cogview2: Faster And Better Text-to-image Generation Via Hierarchical Transformers'
authors: Ming Ding, Wendi Zheng, Wenyi Hong, Jie Tang
conference: Arxiv
year: 2022
bibkey: ding2022cogview2
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.14217'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Ding et al.
---
The development of the transformer-based text-to-image models are impeded by
its slow generation and complexity for high-resolution images. In this work, we
put forward a solution based on hierarchical transformers and local parallel
auto-regressive generation. We pretrain a 6B-parameter transformer with a
simple and flexible self-supervised task, Cross-modal general language model
(CogLM), and finetune it for fast super-resolution. The new text-to-image
system, CogView2, shows very competitive generation compared to concurrent
state-of-the-art DALL-E-2, and naturally supports interactive text-guided
editing on images.