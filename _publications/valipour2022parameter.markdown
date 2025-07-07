---
layout: publication
title: 'Dylora: Parameter Efficient Tuning Of Pre-trained Models Using Dynamic Search-free
  Low-rank Adaptation'
authors: Mojtaba Valipour, Mehdi Rezagholizadeh, Ivan Kobyzev, Ali Ghodsi
conference: Arxiv
year: 2022
citations: 30
bibkey: valipour2022parameter
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.07558'}]
tags: [Training Techniques, GPT, Fine-Tuning, BERT, Model Architecture]
---
With the ever-growing size of pretrained models (PMs), fine-tuning them has
become more expensive and resource-hungry. As a remedy, low-rank adapters
(LoRA) keep the main pretrained weights of the model frozen and just introduce
some learnable truncated SVD modules (so-called LoRA blocks) to the model.
While LoRA blocks are parameter-efficient, they suffer from two major problems:
first, the size of these blocks is fixed and cannot be modified after training
(for example, if we need to change the rank of LoRA blocks, then we need to
re-train them from scratch); second, optimizing their rank requires an
exhaustive search and effort. In this work, we introduce a dynamic low-rank
adaptation (DyLoRA) technique to address these two problems together. Our
DyLoRA method trains LoRA blocks for a range of ranks instead of a single rank
by sorting the representation learned by the adapter module at different ranks
during training. We evaluate our solution on different natural language
understanding (GLUE benchmark) and language generation tasks (E2E, DART and
WebNLG) using different pretrained models such as RoBERTa and GPT with
different sizes. Our results show that we can train dynamic search-free models
with DyLoRA at least 4 to 7 times (depending to the task) faster than LoRA
without significantly compromising performance. Moreover, our models can
perform consistently well on a much larger range of ranks compared to LoRA.