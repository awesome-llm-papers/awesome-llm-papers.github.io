---
layout: publication
title: 'Q8BERT: Quantized 8bit BERT'
authors: Ofir Zafrir, Guy Boudoukh, Peter Izsak, Moshe Wasserblat
conference: Arxiv
year: 2019
citations: 179
bibkey: zafrir2019quantized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.06188'}]
tags: [Training Techniques, Transformer, GPT, Fine-Tuning, Reinforcement Learning,
  BERT, Efficiency and Optimization, Model Architecture, Quantization]
---
Recently, pre-trained Transformer based language models such as BERT and GPT,
have shown great improvement in many Natural Language Processing (NLP) tasks.
However, these models contain a large amount of parameters. The emergence of
even larger and more accurate models such as GPT2 and Megatron, suggest a trend
of large pre-trained Transformer models. However, using these large models in
production environments is a complex task requiring a large amount of compute,
memory and power resources. In this work we show how to perform
quantization-aware training during the fine-tuning phase of BERT in order to
compress BERT by \\(4\times\\) with minimal accuracy loss. Furthermore, the
produced quantized model can accelerate inference speed if it is optimized for
8bit Integer supporting hardware.