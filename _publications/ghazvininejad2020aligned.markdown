---
layout: publication
title: Aligned Cross Entropy For Non-autoregressive Machine Translation
authors: Marjan Ghazvininejad, Vladimir Karpukhin, Luke Zettlemoyer, Omer Levy
conference: Arxiv
year: 2020
bibkey: ghazvininejad2020aligned
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.01655'}]
tags: ["Training Techniques"]
short_authors: Ghazvininejad et al.
---
Non-autoregressive machine translation models significantly speed up decoding
by allowing for parallel prediction of the entire target sequence. However,
modeling word order is more challenging due to the lack of autoregressive
factors in the model. This difficultly is compounded during training with cross
entropy loss, which can highly penalize small shifts in word order. In this
paper, we propose aligned cross entropy (AXE) as an alternative loss function
for training of non-autoregressive models. AXE uses a differentiable dynamic
program to assign loss based on the best possible monotonic alignment between
target tokens and model predictions. AXE-based training of conditional masked
language models (CMLMs) substantially improves performance on major WMT
benchmarks, while setting a new state of the art for non-autoregressive models.