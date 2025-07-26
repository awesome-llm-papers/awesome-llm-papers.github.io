---
layout: publication
title: 'Layerskip: Enabling Early Exit Inference And Self-speculative Decoding'
authors: Mostafa Elhoushi, Akshat Shrivastava, Diana Liskovich, Basil Hosmer, Bram
  Wasti, Liangzhen Lai, Anas Mahmoud, Bilge Acun, Saurabh Agarwal, Ahmed Roman, Ahmed
  A Aly, Beidi Chen, Carole-jean Wu
conference: No Venue
year: 2024
bibkey: elhoushi2024layerskip
additional_links: [{name: Code, url: 'https://github.com/facebookresearch/LayerSkip'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/662b1843ef7a4675bdfd935d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.16710'}]
tags: ["Has Code", "Model Architecture", "Training Techniques"]
short_authors: Elhoushi et al.
---
We present LayerSkip, an end-to-end solution to speed-up inference of large language models (LLMs). First, during training we apply layer dropout, with low dropout rates for earlier layers and higher dropout rates for later layers, and an early exit loss where all transformer layers share the same exit. Second, during inference, we show that this training recipe increases the accuracy of early exit at earlier layers, without adding any auxiliary layers or modules to the model. Third, we present a novel self-speculative decoding solution where we exit at early layers and verify and correct with remaining layers of the model. Our proposed self-speculative decoding approach has less memory footprint than other speculative decoding approaches and benefits from shared compute and activations of the draft and verification stages. We run experiments on different Llama model sizes on different types of training: pretraining from scratch, continual pretraining, finetuning on specific data domain, and finetuning on specific task. We implement our inference solution and show speedups of up to 2.16x on summarization for CNN/DM documents, 1.82x on coding, and 2.0x on TOPv2 semantic parsing task. We open source our code and checkpoints at https://github.com/facebookresearch/LayerSkip.

https://huggingface.co/discussions/paper/662b1843ef7a4675bdfd935d