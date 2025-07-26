---
layout: publication
title: 'Neural-symbolic VQA: Disentangling Reasoning From Vision And Language Understanding'
authors: Kexin Yi, Jiajun Wu, Chuang Gan, Antonio Torralba, Pushmeet Kohli, Joshua
  B. Tenenbaum
conference: Arxiv
year: 2018
bibkey: yi2018neural
citations: 225
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.02338'}]
tags: ["Datasets", "Ethics & Fairness", "Training Techniques"]
short_authors: Yi et al.
---
We marry two powerful ideas: deep representation learning for visual
recognition and language understanding, and symbolic program execution for
reasoning. Our neural-symbolic visual question answering (NS-VQA) system first
recovers a structural scene representation from the image and a program trace
from the question. It then executes the program on the scene representation to
obtain an answer. Incorporating symbolic structure as prior knowledge offers
three unique advantages. First, executing programs on a symbolic space is more
robust to long program traces; our model can solve complex reasoning tasks
better, achieving an accuracy of 99.8% on the CLEVR dataset. Second, the model
is more data- and memory-efficient: it performs well after learning on a small
number of training data; it can also encode an image into a compact
representation, requiring less storage than existing methods for offline
question answering. Third, symbolic program execution offers full transparency
to the reasoning process; we are thus able to interpret and diagnose each
execution step.