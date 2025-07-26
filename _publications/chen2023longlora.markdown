---
layout: publication
title: 'Longlora: Efficient Fine-tuning Of Long-context Large Language Models'
authors: Yukang Chen, Shengju Qian, Haotian Tang, Xin Lai, Zhijian Liu, Song Han,
  Jiaya Jia
conference: No Venue
year: 2023
bibkey: chen2023longlora
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/650ce7f6cbd0c7d550c64dc1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2309.12307'}]
tags: ["Fine-Tuning", "Memory & Context", "Training Techniques"]
short_authors: Chen et al.
---
We present LongLoRA, an efficient fine-tuning approach that extends the context sizes of pre-trained large language models (LLMs), with limited computation cost. Typically, training LLMs with long context sizes is computationally expensive, requiring extensive training hours and GPU resources. For example, training on the context length of 8192 needs 16x computational costs in self-attention layers as that of 2048. In this paper, we speed up the context extension of LLMs in two aspects. On the one hand, although dense global attention is needed during inference, fine-tuning the model can be effectively and efficiently done by sparse local attention. The proposed shift short attention effectively enables context extension, leading to non-trivial computation saving with similar performance to fine-tuning with vanilla attention. Particularly, it can be implemented with only two lines of code in training, while being optional in inference. On the other hand, we revisit the parameter-efficient fine-tuning regime for context expansion. Notably, we find that LoRA for context extension works well under the premise of trainable embedding and normalization. LongLoRA demonstrates strong empirical results on various tasks on LLaMA2 models from 7B/13B to 70B. LongLoRA adopts LLaMA2 7B from 4k context to 100k, or LLaMA2 70B to 32k on a single 8x A100 machine. LongLoRA extends models' context while retaining their original architectures, and is compatible with most existing techniques, like FlashAttention-2. In addition, to make LongLoRA practical, we collect a dataset, LongQA, for supervised fine-tuning. It contains more than 3k long context question-answer pairs.

https://huggingface.co/discussions/paper/650ce7f6cbd0c7d550c64dc1