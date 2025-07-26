---
layout: publication
title: 'Yarn: Efficient Context Window Extension Of Large Language Models'
authors: Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole
conference: No Venue
year: 2023
bibkey: peng2023yarn
additional_links: [{name: Code, url: 'https://github.com/jquesnelle/yarn'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/64f5285ab9a80a053124bb63'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2309.00071'}]
tags: ["Memory & Context"]
short_authors: Peng et al.
---
Rotary Position Embeddings (RoPE) have been shown to effectively encode positional information in transformer-based language models. However, these models fail to generalize past the sequence length they were trained on. We present YaRN (Yet another RoPE extensioN method), a compute-efficient method to extend the context window of such models, requiring 10x less tokens and 2.5x less training steps than previous methods. Using YaRN, we show that LLaMA models can effectively utilize and extrapolate to context lengths much longer than their original pre-training would allow, while also surpassing previous the state-of-the-art at context window extension. In addition, we demonstrate that YaRN exhibits the capability to extrapolate beyond the limited context of a fine-tuning dataset. We publish the checkpoints of Llama 2 7B/13B fine-tuned using YaRN with 64k and 128k context windows at https://github.com/jquesnelle/yarn

https://huggingface.co/discussions/paper/64f5285ab9a80a053124bb63