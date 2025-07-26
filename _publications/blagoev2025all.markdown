---
layout: publication
title: 'All Is Not Lost: LLM Recovery Without Checkpoints'
authors: "Nikolay Blagoev, O\u011Fuzhan Ersoy, Lydia Yiyu Chen"
conference: No Venue
year: 2025
bibkey: blagoev2025all
additional_links: [{name: Code, url: 'https://github.com/gensyn-ai/CheckFree'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/68546c107bc8d012d4ca9939'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.15461'}]
tags: ["Training Techniques"]
short_authors: "Nikolay Blagoev, O\u011Fuzhan Ersoy, Lydia Yiyu Chen"
---
Training LLMs on decentralized and wimpy computation nodes, e.g., multiple on-spot instances, lowers the training cost and enables model democratization. The inevitable challenge here is the churn of nodes due to failures and the operator's scheduling policies, leading to losing a stage - a part of the model. The conventional approaches to recover from failures are to either use checkpointing, where periodically a copy of the entire model is sent to an additional storage, or redundant computation. These approaches yield significant communication and/or computation overhead even in non-failure cases and scale poorly in settings with large models. In this paper, we propose, CheckFree, an efficient recovery method where a failing stage is substituted by a weighted average of the closest neighboring stages. In contrast to the state of the art, CheckFree requires no additional computation or storage. However, because of the nature of averaging neighbouring stages, it can only recover failures of intermediate stages. We further extend our method to CheckFree+ with out-of-order pipeline execution to tolerate crashes of the first and last stages. Thanks to out-of-order pipelining, behaviour of those stages is mimicked by their neighboring ones, which allows CheckFree+ to recover them by simply copying the weights from the immediate neighbour. To be able to recover the (de)embedding layers, CheckFree+ copies those layers to the neighboring stages, which requires relatively small storage overhead. We extensively evaluate our method on LLaMa models of model sizes from 124M to 1.5B with varying failure frequencies. In the case of low and medium failure rates (5-10%), CheckFree and CheckFree+ outperform both checkpointing and redundant computation in terms of convergence in wall-clock time by over 12%. Both of our proposals can be run via our code available at: https://github.com/gensyn-ai/CheckFree.

https://huggingface.co/discussions/paper/68546c107bc8d012d4ca9939