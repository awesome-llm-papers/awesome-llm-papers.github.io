---
layout: publication
title: One-minute Video Generation With Test-time Training
authors: Karan Dalal, Daniel Koceja, Gashon Hussein, Jiarui Xu, Yue Zhao, Youjin Song,
  Shihao Han, Ka Chun Cheung, Jan Kautz, Carlos Guestrin, Tatsunori Hashimoto, Sanmi
  Koyejo, Yejin Choi, Yu Sun, Xiaolong Wang
conference: No Venue
year: 2025
bibkey: dalal2025one
additional_links: [{name: Code, url: 'https://test-time-training.github.io/video-dit'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67f4a0cefefcc542f83f8592'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.05298'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Dalal et al.
---
Transformers today still struggle to generate one-minute videos because self-attention layers are inefficient for long context. Alternatives such as Mamba layers struggle with complex multi-scene stories because their hidden states are less expressive. We experiment with Test-Time Training (TTT) layers, whose hidden states themselves can be neural networks, therefore more expressive. Adding TTT layers into a pre-trained Transformer enables it to generate one-minute videos from text storyboards. For proof of concept, we curate a dataset based on Tom and Jerry cartoons. Compared to baselines such as Mamba~2, Gated DeltaNet, and sliding-window attention layers, TTT layers generate much more coherent videos that tell complex stories, leading by 34 Elo points in a human evaluation of 100 videos per method. Although promising, results still contain artifacts, likely due to the limited capability of the pre-trained 5B model. The efficiency of our implementation can also be improved. We have only experimented with one-minute videos due to resource constraints, but the approach can be extended to longer videos and more complex stories. Sample videos, code and annotations are available at: https://test-time-training.github.io/video-dit

https://huggingface.co/discussions/paper/67f4a0cefefcc542f83f8592