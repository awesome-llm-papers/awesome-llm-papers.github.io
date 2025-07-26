---
layout: publication
title: 'Worldvla: Towards Autoregressive Action World Model'
authors: Jun Cen, Chaohui Yu, Hangjie Yuan, Yuming Jiang, Siteng Huang, Jiayan Guo,
  Xin Li, Yibing Song, Hao Luo, Fan Wang, Deli Zhao, Hao Chen
conference: No Venue
year: 2025
bibkey: cen2025worldvla
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.21539'}]
tags: ["Tools"]
short_authors: Cen et al.
---
We present WorldVLA, an autoregressive action world model that unifies action and image understanding and generation. Our WorldVLA intergrates Vision-Language-Action (VLA) model and world model in one single framework. The world model predicts future images by leveraging both action and image understanding, with the purpose of learning the underlying physics of the environment to improve action generation. Meanwhile, the action model generates the subsequent actions based on image observations, aiding in visual understanding and in turn helps visual generation of the world model. We demonstrate that WorldVLA outperforms standalone action and world models, highlighting the mutual enhancement between the world model and the action model. In addition, we find that the performance of the action model deteriorates when generating sequences of actions in an autoregressive manner. This phenomenon can be attributed to the model's limited generalization capability for action prediction, leading to the propagation of errors from earlier actions to subsequent ones. To address this issue, we propose an attention mask strategy that selectively masks prior actions during the generation of the current action, which shows significant performance improvement in the action chunk generation task.

https://huggingface.co/discussions/paper/685e06f871131fa43be08aca