---
layout: publication
title: How Good Are Low-bit Quantized Llama3 Models? An Empirical Study
authors: Wei Huang, Xudong Ma, Haotong Qin, Xingyu Zheng, Chengtao Lv, Hong Chen,
  Jie Luo, Xiaojuan Qi, Xianglong Liu, Michele Magno
conference: No Venue
year: 2024
bibkey: huang2024how
additional_links: [{name: Code, url: 'https://github.com/Macaronlin/LLaMA3-Quantization'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.14047'}]
tags: ["Efficiency", "Fine-Tuning", "Has Code", "Training Techniques"]
short_authors: Huang et al.
---
Meta's LLaMA family has become one of the most powerful open-source Large Language Model (LLM) series. Notably, LLaMA3 models have recently been released and achieve impressive performance across various with super-large scale pre-training on over 15T tokens of data. Given the wide application of low-bit quantization for LLMs in resource-limited scenarios, we explore LLaMA3's capabilities when quantized to low bit-width. This exploration holds the potential to unveil new insights and challenges for low-bit quantization of LLaMA3 and other forthcoming LLMs, especially in addressing performance degradation problems that suffer in LLM compression. Specifically, we evaluate the 10 existing post-training quantization and LoRA-finetuning methods of LLaMA3 on 1-8 bits and diverse datasets to comprehensively reveal LLaMA3's low-bit quantization performance. Our experiment results indicate that LLaMA3 still suffers non-negligent degradation in these scenarios, especially in ultra-low bit-width. This highlights the significant performance gap under low bit-width that needs to be bridged in future developments. We expect that this empirical study will prove valuable in advancing future models, pushing the LLMs to lower bit-width with higher accuracy for being practical. Our project is released on https://github.com/Macaronlin/LLaMA3-Quantization and quantized LLaMA3 models are released in https://huggingface.co/LLMQ.

https://huggingface.co/discussions/paper/662712bf97eadbff167d0cbf