---
layout: publication
title: 'Maskllm: Learnable Semi-structured Sparsity For Large Language Models'
authors: Gongfan Fang, Hongxu Yin, Saurav Muralidharan, Greg Heinrich, Jeff Pool,
  Jan Kautz, Pavlo Molchanov, Xinchao Wang
conference: No Venue
year: 2024
bibkey: fang2024maskllm
additional_links: [{name: Code, url: 'https://github.com/NVlabs/MaskLLM'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66f61ce5b35008620e525882'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2409.17481'}]
tags: ["Efficiency", "Has Code", "Model Architecture"]
short_authors: Fang et al.
---
Large Language Models (LLMs) are distinguished by their massive parameter counts, which typically result in significant redundancy. This work introduces MaskLLM, a learnable pruning method that establishes Semi-structured (or ``N:M'') Sparsity in LLMs, aimed at reducing computational overhead during inference. Instead of developing a new importance criterion, MaskLLM explicitly models N:M patterns as a learnable distribution through Gumbel Softmax sampling. This approach facilitates end-to-end training on large-scale datasets and offers two notable advantages: 1) High-quality Masks - our method effectively scales to large datasets and learns accurate masks; 2) Transferability - the probabilistic modeling of mask distribution enables the transfer learning of sparsity across domains or tasks. We assessed MaskLLM using 2:4 sparsity on various LLMs, including LLaMA-2, Nemotron-4, and GPT-3, with sizes ranging from 843M to 15B parameters, and our empirical results show substantial improvements over state-of-the-art methods. For instance, leading approaches achieve a perplexity (PPL) of 10 or greater on Wikitext compared to the dense model's 5.12 PPL, but MaskLLM achieves a significantly lower 6.72 PPL solely by learning the masks with frozen weights. Furthermore, MaskLLM's learnable nature allows customized masks for lossless application of 2:4 sparsity to downstream tasks or domains. Code is available at https://github.com/NVlabs/MaskLLM.

https://huggingface.co/discussions/paper/66f61ce5b35008620e525882