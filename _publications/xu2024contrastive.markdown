---
layout: publication
title: 'Contrastive Preference Optimization: Pushing The Boundaries Of LLM Performance
  In Machine Translation'
authors: Haoran Xu, Amr Sharaf, Yunmo Chen, Weiting Tan, Lingfeng Shen, Benjamin van
  Durme, Kenton Murray, Young Jin Kim
conference: No Venue
year: 2024
bibkey: xu2024contrastive
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65a776634908b2676c709a74'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.08417'}]
tags: ["Datasets", "Efficiency", "Fine-Tuning", "Model Architecture"]
short_authors: Xu et al.
---
Moderate-sized large language models (LLMs) -- those with 7B or 13B parameters -- exhibit promising machine translation (MT) performance. However, even the top-performing 13B LLM-based translation models, like ALMA, does not match the performance of state-of-the-art conventional encoder-decoder translation models or larger-scale LLMs such as GPT-4. In this study, we bridge this performance gap. We first assess the shortcomings of supervised fine-tuning for LLMs in the MT task, emphasizing the quality issues present in the reference data, despite being human-generated. Then, in contrast to SFT which mimics reference translations, we introduce Contrastive Preference Optimization (CPO), a novel approach that trains models to avoid generating adequate but not perfect translations. Applying CPO to ALMA models with only 22K parallel sentences and 12M parameters yields significant improvements. The resulting model, called ALMA-R, can match or exceed the performance of the WMT competition winners and GPT-4 on WMT'21, WMT'22 and WMT'23 test datasets.

https://huggingface.co/discussions/paper/65a776634908b2676c709a74